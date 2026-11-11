# Joseph Ogle

**B.S. Computer Science** · Southern Illinois University Edwardsville · December 2025

<img src="assets/rule.svg" alt="" width="100%">

My background is in both computer science and IT, including IT work at LCMS Foundation. The public projects are vehicle-network tools and Windows utilities.

I am studying for Microsoft AZ-104. That exam is in progress, and I am not certified.

I am aiming for aerospace and defense software and test roles.

[78tacos.github.io](https://78tacos.github.io)

## Current project

### [AeroTest](https://github.com/78tacos/AeroTest) · in progress

Educational C++20 avionics bus simulator and test-automation platform. The sequence is CAN first, MIL-STD-1553 later, then a test runner, fault injection, and traceability.

The repository describes it as a learning project: not certified or flight software.

**[Build log](https://78tacos.github.io/blog/) — coming soon.**

## Selected work

CANtrol Center is the SIUE senior capstone. CAN-Dashboard applies CAN to an electric train. Ferry, uproot, and Corral are the Windows tools from the IT side. dns-bench measures DNS resolvers. cog-locations keeps a public directory up to date.

### Vehicle networks

**CANtrol Center** — SIUE senior capstone, team project.

**[CANServer](https://github.com/78tacos/CANServer)** — C++20 multithreaded TCP server and a small client that schedule recurring and one-shot `cansend` frames on Linux CAN and vCAN interfaces. A timer thread hands work to a priority pool.

**[DBCFileViewer](https://github.com/78tacos/DBCFileViewer)** — Qt 6 Quick/QML DBC file viewer (C++17) and the TCP client for that scheduler. Team frontend, also published as [dnasso/DBCFileViewer](https://github.com/dnasso/DBCFileViewer).

**[CAN-Dashboard](https://github.com/78tacos/CAN-Dashboard)** — Web dashboard for CAN data from an electric train: speed, battery, voltage, current, temperature, fan speed, power, and odometer, using the frame layout in `demo.dbc`, and a map of a Harrisburg–Pittsburgh route. The page can simulate those values. With the WebSocket up, it also applies frames from the bus. On Linux, the server opens SocketCAN `vcan0`.

### Windows systems

**[Ferry](https://github.com/78tacos/Ferry)** — Moves files, settings, and programs from an old Windows PC to a new one. WPF wizard for a person at the keyboard, and `ferry-cli` for scripted migrations. .NET.

**[uproot](https://github.com/78tacos/uproot)** — Uninstalls a Windows program, then finds what the uninstaller left behind and removes it, with backups and undo. It began as the uninstaller inside [WGUpdater](https://github.com/LCMS-Foundation/wgupdater). .NET and WPF.

**[Corral](https://github.com/78tacos/Corral)** — Desktop fences for Windows: translucent containers for shortcuts, files, and folders. WPF on .NET 10. Shortcuts are copied into Corral. Files and folders stay where they are.

### Network measurement

**[dns-bench](https://github.com/78tacos/dns-bench)** — Go command-line tool that measures DNS resolvers from the network it runs on: cached and uncached latency, plus loss. It can write a ranked table, JSON, CSV, or HTML. v1 is IPv4, UDP port 53.

### A public directory

**[cog-locations](https://github.com/78tacos/cog-locations)** — Map and printable directory of Church of God congregations, built because the official locator was hard to search. A Python script downloads the locator pages, parses them, and geocodes addresses. GitHub Actions refreshes the data monthly. [Live map](https://78tacos.github.io/cog-locations/).

## Toolkit

<p>
  <a href="https://github.com/78tacos/CANServer"><img alt="C++" src="https://img.shields.io/badge/C%2B%2B-3D5A73?style=flat-square&amp;logo=cplusplus&amp;logoColor=white"></a>
  <a href="https://github.com/78tacos/DBCFileViewer"><img alt="Qt" src="https://img.shields.io/badge/Qt-3D5A73?style=flat-square&amp;logo=qt&amp;logoColor=white"></a>
  <a href="https://github.com/78tacos/Ferry"><img alt="C#" src="https://img.shields.io/badge/C%23-3D5A73?style=flat-square"></a>
  <a href="https://github.com/78tacos/uproot"><img alt=".NET" src="https://img.shields.io/badge/.NET-3D5A73?style=flat-square&amp;logo=dotnet&amp;logoColor=white"></a>
  <a href="https://github.com/78tacos/cog-locations"><img alt="Python" src="https://img.shields.io/badge/Python-3D5A73?style=flat-square&amp;logo=python&amp;logoColor=white"></a>
  <a href="https://github.com/78tacos/dns-bench"><img alt="Go" src="https://img.shields.io/badge/Go-3D5A73?style=flat-square&amp;logo=go&amp;logoColor=white"></a>
  <a href="https://github.com/78tacos/CAN-Dashboard"><img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-3D5A73?style=flat-square&amp;logo=javascript&amp;logoColor=white"></a>
  <a href="https://github.com/78tacos/shiftledger"><img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3D5A73?style=flat-square&amp;logo=typescript&amp;logoColor=white"></a>
</p>

Each badge links to a repository that uses that stack. AZ-104 stays in the introduction: it is still exam study.

Also in the repositories: Linux, Windows, Docker, Kotlin, PostgreSQL, HTML/CSS, PowerShell, and SocketCAN. CANServer, Ferry, uproot, Corral, dns-bench, and cog-locations include tests.

## Outside of code

Health, and car repair. Car repair connects to the bus work through CAN and OBD-II diagnostics.

[78tacos.github.io](https://78tacos.github.io)
