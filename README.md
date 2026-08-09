# NetAn
## Directory Structure(not fixed)
```text
kali-dist-scanner/
├── CMakeLists.txt          # Main build configuration script
├── README.md               # Documentation and usage
├── config/                 # Configuration files for deployment
│   ├── controller.conf
│   └── agent.conf
├── systemd/                # Service files to run the scanner in background
│   ├── kali-scanner-controller.service
│   └── kali-scanner-agent.service
└── src/                    # C++ Source code
    ├── common/             # Shared protocol headers and structures
    │   └── protocol.hpp
    ├── controller/         # Controller source files
    │   ├── main.cpp
    │   └── epoll_server.cpp
    └── agent/              # Agent source files
        ├── main.cpp
        └── raw_scanner.cpp
```
