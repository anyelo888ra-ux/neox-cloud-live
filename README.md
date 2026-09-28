# NEOX Cloud Live ☁️

**NEOX Cloud Live v2.1** is a browser-based NEOX cloud/server simulator. It is intentionally local: cookies keep the NEOX identity and `localStorage` keeps the simulated cloud state. No database and no real payment system are required.

## v2.1 headline features

- 🖥️ 5 free simulated servers.
- ⭐ Premium simulation expands the profile to 10 simulated servers.
- 🆔 NEOX IDs from 1 to 9,999,999 stored in a cookie.
- 💾 Server state stored locally in `localStorage`.
- 📊 CPU, RAM, storage, network, bandwidth and uptime.
- 🧩 Processes and service manager.
- 🌐 Ports, DNS and simulated firewall.
- 📁 Virtual files.
- 👥 Users and roles.
- 📝 Logs and audit trail.
- 💾 Local backups and snapshots.
- ⏰ Scheduled-task simulation.
- 📦 Container simulation.
- 🔌 API simulation.
- 🧪 Diagnostics and failure simulation.
- 🧰 Server templates and resource quotas.
- 🧠 110-feature matrix.
- 💳 Premium is **100% simulated**. No real card, payment provider, charge, or money movement exists.

## Premium pricing simulation

The starting simulated price is **$1/month**.

Every simulated 30-day period increases the displayed subscription price by **$1**:

`$1 → $2 → $3 → $4 → ...`

Activating Premium does **not** charge real money. The price is only part of the game/simulator economy. The activation date is stored locally, so the displayed price can advance while the same profile returns later.

Premium currently unlocks:
- 10 server slots.
- Snapshots.
- Local backups.
- Scheduled tasks.
- Firewall controls.
- Port manager.
- DNS tools.
- Service manager.
- API simulator.
- Container simulator.
- Server templates.
- Resource quotas.
- Audit trail.

## 110-feature matrix

1. Five base virtual servers
2. Ten-server Premium expansion
3. Persistent NEOX identity
4. Cookie identity storage
5. Local profile storage
6. CPU metrics
7. RAM metrics
8. Storage metrics
9. Latency metrics
10. Bandwidth metrics
11. Uptime clock
12. Online/offline state
13. Start command
14. Stop command
15. Restart command
16. Server switching
17. Process list
18. Process stop simulation
19. Network interface
20. Virtual file list
21. Virtual file creation
22. Local users
23. Permission roles
24. Extended console
25. Live logs
26. Persistent logs
27. Random events
28. Incident simulation
29. Incident recovery
30. Diagnostics
31. System update simulation
32. Notification setting
33. Hostname setting
34. Server modes
35. Performance mode
36. Eco mode
37. Maintenance mode
38. Standard mode
39. Console clear
40. whoami command
41. help command
42. Server overview
43. Server cards
44. Active-server marker
45. Responsive layout
46. Browser-only execution
47. No host shell execution
48. Automatic metrics
49. Automatic events
50. Process supervisor
51. Storage simulation
52. Network simulation
53. Health checks
54. Boot logs
55. Recovery logs
56. Update logs
57. Settings logs
58. Per-server state
59. Per-server hostnames
60. Server numbering
61. Cloud dashboard
62. Console UI
63. Metric bars
64. Status indicators
65. Event counter
66. Process counter
67. File counter
68. User roles panel
69. Network panel
70. Diagnostics panel
71. Incident panel
72. Settings panel
73. Profile separation
74. Server reset
75. New identity
76. Identity restoration
77. Profile storage key
78. Virtual /system
79. Virtual /config
80. Virtual /logs
81. Virtual /home
82. Simulated LAN
83. Dynamic latency
84. Dynamic bandwidth
85. Resource fluctuation
86. Performance load
87. Eco load reduction
88. Maintenance workflow
89. Persistent configuration
90. Persistent processes
91. Persistent files
92. Persistent logs
93. Persistent incidents
94. Persistent metrics
95. Safe simulation architecture
96. Failure-testing workflow
97. Expansion-ready architecture
98. Future realtime adapter
99. Future multiplayer adapter
100. Optional backend adapter
101. Continuous update roadmap
102. Snapshots
103. Local backups
104. Scheduled tasks
105. Firewall simulation
106. Port manager
107. DNS simulation
108. Service manager
109. API simulator
110. Container/server-template/quota/audit premium toolset

## Console commands

`help`, `status`, `servers`, `switch N`, `start`, `stop`, `restart`, `processes`, `kill PID`, `network`, `ports`, `open PORT`, `close PORT`, `dns`, `files`, `touch NAME`, `users`, `services`, `service NAME`, `backup`, `snapshot`, `tasks`, `task NAME`, `firewall [on|off]`, `container NAME`, `api`, `template`, `quota`, `audit`, `incident`, `recover`, `diagnose`, `update`, `event`, `notify`, `settings`, `mode X`, `features`, `premium`, `clear`, `reset`, `whoami`.

## Persistence model

```
Cookie
└── NEOX ID

localStorage
└── neox-cloud-v2.1:<NEOX ID>
    ├── profile
    ├── servers
    ├── logs
    ├── settings
    ├── snapshots
    └── premium simulation
```

This is intentionally **not multiplayer synchronization**. Another browser/device has a different local storage area. Shared control of the same server by many people will require a realtime backend later.

## Bug-fix focus in v2.1

- Safe HTML escaping for dynamic logs, file names and server names.
- Restored uptime display.
- Per-server persistence.
- More robust loading when old profiles are missing optional arrays.
- Premium server capacity is expanded only in the local simulation.
- Premium controls are visibly gated.
- Console errors use explicit messages.
- No arbitrary host command execution.
- No real billing or payment integration.

## Scope

NEOX Cloud Live is a simulation/lab, not a real cloud provider. It does not execute arbitrary commands on the user's computer or a remote host.

## Future

- Shared realtime state.
- Multiplayer permissions.
- Public/private server modes.
- Server invitations.
- More advanced virtual filesystems.
- Simulated containers and orchestration.
- Optional authorized real-server mode.
