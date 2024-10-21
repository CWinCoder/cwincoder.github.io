---
layout: post
title:  ":newspaper:&nbspNative WinUI 3 Applications: A Modern Challenge"
categories: MSVC SDK WinUI3
---

Compiling a native WinUI 3 application outside the Visual Studio ecosystem can feel like an obstacle course. For command line aficionados and makefile enthusiasts, the journey is no longer as straightforward as downloading a C/C++ compiler and the Windows SDK. The process has evolved, and with it, the complexity has increased.

## What you need nowadays:

- A C/C++ compiler toolchain (Visual C++, available as a standalone tool)
- The Windows SDK
- The Windows App SDK
- The latest C/C++ headers (generated from the Windows App SDK)
- And a ton of patience and perseverance, as the path is strewn with pitfalls!

### Visual C++ compiler
The Visual C++ compiler, part of Microsoft’s Visual Studio suite, is a powerful tool for building applications that leverage the C++ programming language.
It provides advanced optimization features, robust debugging capabilities, and excellent support for modern C++ standards, making it an indispensable tool for Windows development. 
Its integration with the Windows SDK and App SDK allows developers to create high-performance applications tailored for Windows platforms.

### Windows SDK
The Windows Software Development Kit (SDK) provides the low-level tools, libraries, headers, and documentation needed for developing native Windows applications.
It includes crucial Windows APIs and functions that allow developers to interact with the core components of the Windows operating system, enabling deep integration and customization.

### Windows App SDK
The Windows App SDK, formerly known as *Project Reunion*, is a modern framework that aims to bridge the gap between different Windows app development technologies.
It provides a unified platform for building Windows apps using **WinUI 3**, **MSIX**, and other modern tools, making it easier to create applications that can leverage the latest Windows features.
While the description on paper seems great, in practice, it’s very challenging to use outside the Visual Studio ecosystem, requiring significant effort and expertise.

Using all these components to create modern native C/C++ applications is a real challenge, when you only use the command line.
The next articles will detail a little more everything I was able to discover and will hopefully help you.
