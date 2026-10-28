# Third-party notices

REA-authored code is licensed under [MIT](LICENSE).

Copyright (c) 2020-2026 Bryan Kwandou. All rights reserved.

This project is authored, designed, and maintained solely by Bryan Kwandou (Vincentius Bryan Kwandou). No external contributors or third-party authors contributed to the REA codebase.

This document inventories external software dependencies, libraries, and runtime tools that may be utilized or inspected in technical workflows. Project and package names identify technical integrations only; they do not imply affiliation, sponsorship, or external contribution to this project.

## Technical Dependencies and Runtime Tools

| Component | License | Role in REA |
| --- | --- | --- |
| npm dependencies | Various ([Inventory](licenses/npm-dependencies.txt)) | Node.js runtime and development packages defined in package.json |
| PE ordinal lookup | MIT | Static ordinal name lookup tables for PE binary analysis |
| NativeAOT parser | MIT | NativeAOT format parser and structure definitions |
| EVM analysis | MIT | Bytecode analysis tooling for EVM contracts |
| Windows native addon | MinGW-w64 / GCC Runtime / MIT | Addon build headers and static runtime libraries |

## Tool Integrations

The tools listed below are independently distributed, external binaries that users may optionally install in their own local environments for specific reverse engineering workflows. REA provides local CLI/MCP interfaces to interact with these external tools when installed:

| Tool | License | Integration Type |
| --- | --- | --- |
| Ghidra | Apache-2.0 | Optional user-installed headless binary analysis |
| JADX | Apache-2.0 | Optional user-installed Android decompiler |
| Apktool | Apache-2.0 | Optional user-installed Android resource decoder |
| Binwalk | MIT | Optional user-installed firmware analysis utility |
| Unblob | MIT | Optional user-installed archive extractor |
| WABT | Apache-2.0 | Optional user-installed WebAssembly toolkit |
| LLDB / GDB | Apache-2.0 / GPL-3.0 | Optional user-installed system debuggers |

All external tools retain their respective licenses and terms. REA does not bundle, relicense, or distribute commercial or proprietary software.
