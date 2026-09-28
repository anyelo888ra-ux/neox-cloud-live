# NEOX Cloud Live ☁️

**NEOX Cloud Live v1.0** is a browser-based NEOX server simulator designed to keep evolving without requiring a database for its local profile.

## v1.0

The simulator now provides **5 virtual servers per local NEOX identity**. Each browser profile receives a random **NEOX ID from 1 to 9,999,999**. The ID is stored in a cookie, while server state is persisted in browser `localStorage`.

### Important persistence note

- 🍪 Cookie = persistent NEOX identity.
- 💾 localStorage = persistent simulated server data.
- 🚫 No database is required for this local persistence.
- 🔒 Data stays in that browser/profile; it is **not shared across different devices or browsers**.
- 🌐 A true shared multiplayer cloud will require a server/realtime backend later.

## v1.0 feature plan — 100 features

1. 🖥️ Five virtual servers
2. 🆔 Persistent NEOX identity
3. 🍪 Cookie-based identity
4. 💾 Local persistent server state
5. 📊 CPU metrics
6. 📊 RAM metrics
7. 📊 Storage metrics
8. 🌐 Latency metrics
9. 📡 Bandwidth metrics
10. ⏱️ Server uptime
11. 🟢 Online/offline state
12. ▶️ Start server
13. ⏹️ Stop server
14. 🔄 Restart server
15. 🔀 Switch active server
16. 🧩 Process list
17. 🛑 Simulated process stopping
18. 🌐 Simulated network interface
19. 📁 Virtual file list
20. ➕ Virtual file creation
21. 👥 Local users
22. 🔐 Permission roles
23. 🛠️ Extended console
24. 📜 Live logs
25. 🧾 Persistent event history
26. ⚡ Random server events
27. 🚨 Simulated incidents
28. 🧯 Incident recovery
29. 🧪 Diagnostics
30. 🔄 Simulated system updates
31. 🔔 Notification setting
32. 🎛️ Hostname setting
33. ⚙️ Server mode setting
34. 🚀 Performance mode
35. 🌱 Eco mode
36. 🛠️ Maintenance mode
37. 📦 Standard mode
38. 🧹 Console clear
39. 👤 `whoami`
40. 📋 `help`
41. 📈 Server overview
42. 🖥️ Server cards
43. 🎯 Active-server indicator
44. 📱 Responsive layout
45. 🧑‍💻 Browser-only command execution
46. 🛡️ No arbitrary host shell execution
47. 🔁 Automatic metric simulation
48. 🔁 Automatic event simulation
49. 🧠 Process supervisor simulation
50. 💽 Storage usage simulation
51. 🌐 Network status simulation
52. 🧪 Health-check simulation
53. 📝 Boot log simulation
54. 📝 Recovery logs
55. 📝 Update logs
56. 📝 Settings logs
57. 🧱 Per-server state separation
58. 🏷️ Per-server hostnames
59. 🔢 Server numbering
60. ☁️ Cloud-style dashboard
61. 💻 NEOX console UI
62. 📊 Metric progress bars
63. 🟢 Status indicators
64. 📟 Event counter
65. 🔎 Process count
66. 📂 File count
67. 👥 User count representation
68. 📡 Network details panel
69. 🧪 Diagnostics panel
70. 🚨 Incident panel
71. 🎛️ Settings panel
72. 🔐 Local profile separation
73. ♻️ Server reset
74. 🆕 New NEOX identity
75. 🔑 Identity restoration on return
76. 🧠 Profile-specific storage key
77. 🗂️ Virtual /system
78. 🗂️ Virtual /config
79. 🗂️ Virtual /logs
80. 🗂️ Virtual /home
81. 🛰️ Simulated LAN mode
82. 📶 Dynamic latency
83. 📶 Dynamic bandwidth
84. 📉 Resource fluctuation
85. 📈 Performance-mode load
86. 🌱 Eco-mode load reduction
87. 🚧 Maintenance-mode support
88. 🧾 Persistent configuration
89. 🧾 Persistent process state
90. 🧾 Persistent virtual files
91. 🧾 Persistent logs
92. 🧾 Persistent incidents
93. 🧾 Persistent metrics
94. 🧰 Safe browser simulation architecture
95. 🧪 Failure-testing workflow
96. 🏗️ Multi-server architecture ready for expansion
97. 🌍 Ready for future shared realtime state
98. 👥 Ready for future multi-user control
99. 🗄️ Ready for optional backend persistence
100. 🚀 Continuous-update roadmap

## Console commands

`help`, `status`, `servers`, `switch N`, `start`, `stop`, `restart`, `processes`, `kill PID`, `network`, `files`, `touch NAME`, `users`, `logs`, `event`, `incident`, `recover`, `diagnose`, `update`, `notify`, `settings`, `mode X`, `clear`, `reset`, `whoami`.

## Future multiplayer architecture

The local v1.0 architecture intentionally does **not** pretend that cookies can synchronize users. For a future public multiplayer mode:

1. Each visitor keeps their NEOX identity.
2. Up to five virtual servers can belong to that profile.
3. A realtime service synchronizes authorized actions.
4. Server ownership and permissions are checked server-side.
5. The browser remains the dashboard.
6. A backend can be added later without throwing away the simulator UI.

## Safety / scope

This project is a **simulation**. Its console does not execute arbitrary commands on the user's computer or server. It is intended as a browser lab for experimenting with cloud/server concepts.

## Roadmap after v1.0

- Shared realtime state between visitors
- Multi-user permissions
- Public/private server modes
- Server invitations
- More virtual filesystems
- Snapshots and restore points
- Simulated containers
- Service manager
- Task scheduler
- API simulator
- Optional authorized real-server mode
