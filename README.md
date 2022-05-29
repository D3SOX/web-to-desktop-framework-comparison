# Web to Desktop framework comparison

This repository was made to create an objective comparison of multiple framework that grant us to "transform" our web app to desktop application formats.

## Table Of Content
- [Major characteristics](#major-characteristics)
- [Operating systems](#operating-systems)
- [Benchmarks](#benchmarks)
  * [01 - Empty app](#01---empty-app)
  * [02 - Empty app (Headless)](#02---empty-app-headless)

## Major characteristics

| | [Electron](https://github.com/electron/electron) | [NW.JS](https://github.com/nwjs/nw.js) | [Tauri](https://github.com/tauri-apps/tauri) | [NodeGui](https://github.com/nodegui/nodegui) |  [Neutralino](https://github.com/neutralinojs/neutralinojs) | [Flutter](https://github.com/flutter/flutter) | [.Net MAUI](https://github.com/dotnet/maui) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Github stars** | 102k | 39k | 37k | 8k | 6k | 139k | 15k |
| **Forks** | 14k | 4k | 0.9k | 0.2k | 0.2k | 22k | 0.9k |
| **Creation date** | 2013 | 2011 | 2019 | 2019 | 2018 | 2018 | 2020 |
| **Last Update** | 2021 | 2021 | 2021 | 2021 | 2021 | 2021 | 2021 |
| **Framework Language** | C++, JS, Objective-C, Python | C++ | Rust | C++ | C++ | C, C++, Dart | C# |
| **Usage Language - Back** | JS, C++ | JS, C++ | Rust | JS, C++ | JS, C++ | Dart | C# |
| **Usage Language - Front** | HTML, CSS, JS | HTML, CSS, JS | HTML, CSS, JS | HTML, CSS, JS | HTML, CSS, JS | Dart | C# |
| **License** | [MIT](https://github.com/electron/electron/blob/master/LICENSE) | [MIT](https://github.com/nwjs/nw.js/blob/nw52/LICENSE) | [MIT](https://github.com/tauri-apps/tauri/blob/dev/LICENSE) | [MIT](https://github.com/nodegui/nodegui/blob/master/LICENSE) | [MIT](https://github.com/neutralinojs/neutralinojs/blob/master/LICENSE) | [BSD 3-Clause](https://github.com/flutter/flutter/blob/master/LICENSE) | [MIT](https://github.com/dotnet/maui/blob/main/LICENSE) |
| **Developer Dependencies** | [Node.js, Electron NPM Package](https://www.electronjs.org/docs/tutorial/quick-start#prerequisites) | [Node.js, NW.JS SDK](https://nwjs.readthedocs.io/en/latest/For%20Users/Getting%20Started/) | [C++ Compiler, Node.js, Rustc, Cargo](https://tauri.studio/docs/getting-started/prerequisites/) | [Cmake, make, Node.js, NodeGUI NPM Package](https://docs.nodegui.org/docs/guides/getting-started/#developer-environment) | [Node.js, Neu NPM Package](https://neutralino.js.org/docs/#/gettingstarted/quickstart) | [Flutter SDK, Visual Studio 2019 / Clang](https://flutter.dev/desktop#requirements) | [.Net SDK, Visual Studio (optionnal), WebView2 (optionnal), Xcode (optionnal)](https://github.com/dotnet/maui/wiki/Getting-Started) |
| **User Dependencies** | None | None | None | None | None | None | None |
| **npm/yarn module support** | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ |
| **Engine** | Chromium | Webkit, Chromium | WRY (WebKitGTK for Linux, WebKit for MacOS, Webview2 for Windows) | Qt | WebkitGTK+ | Flutter engine | .NET MAUI |

## Operating systems support

|  |  | [Electron](https://github.com/electron/electron) | [NW.JS](https://github.com/nwjs/nw.js) | [Tauri](https://github.com/tauri-apps/tauri) | [NodeGui](https://github.com/nodegui/nodegui) |  [Neutralino](https://github.com/neutralinojs/neutralinojs) | [Flutter](https://github.com/flutter/flutter) | [.Net MAUI](https://github.com/dotnet/maui) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Developement Environment** | ***Windows*** | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| | ***MacOS*** | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| | ***Linux*** | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| **Target Environment** | ***Windows*** | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| | ***MacOS*** | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| | ***Linux*** | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | Soon |
| | ***Android*** | ❌ | [Requested](https://github.com/nwjs/nw.js/issues/94) | Soon<sup>1</sup> | ❌ | ❌ | ✔️ | ✔️ |
| | ***iOS*** | ❌ | ❌ | In progress<sup>1</sup> | ❌ | ❌ | ✔️ | ✔️ |
| | ***tvOS*** | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ |
| | ***Web*** | ❌ | ❌ | ❌ | ❌ | ✔️<sup>2</sup> | ✔️ | ❌ |

**<sup>1</sup>**: https://github.com/tauri-apps/tauri#platforms  
**<sup>2</sup>**: Uses [modes](https://neutralino.js.org/docs/configuration/modes/) to generate web apps  

## Benchmarks

**See [benchmarks.json](https://github.com/Elanis/web-to-desktop-framework-comparison/blob/main/runner/benchmarks.json) to get more informations about following data.**


# 01-empty-app

See source in [benchmark/01-empty-app](https://github.com/Elanis/web-to-desktop-framework-comparison/tree/main/benchmark/01-empty-app/) folder.

|  |  | [Electron](https://github.com/electron/electron) | [NW.JS](https://github.com/nwjs/nw.js) | [Tauri](https://github.com/tauri-apps/tauri) | [NodeGui](https://github.com/nodegui/nodegui) | [Neutralino](https://github.com/neutralinojs/neutralinojs) | [Flutter](https://github.com/flutter/flutter) | [.Net MAUI](https://github.com/dotnet/maui) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Build size** | ***Windows (x86)*** | ≈160MB | ≈237MB | ? | ≈83MB | ≈2MB | ≈18MB | ? |
| | ***Windows (ARM64)*** | ≈193MB | [Requested](https://github.com/nwjs/nw.js/issues/7599) | ? | ? | ? | ? | ? |
| | ***Linux (x86)*** | ≈171MB | ≈329MB | ? | ? | ≈2MB | ? | ? |
| | ***Linux (ARMv7l)*** | ≈128MB | [Requested](https://github.com/nwjs/nw.js/issues/1151) | ? | ? | ? | ? | ? |
| | ***Linux (ARM64)*** | ≈196MB | [Requested](https://github.com/nwjs/nw.js/issues/1151) | ? | ? | ? | ? | ? |
| **Memory Usage** | ***Windows (x64)*** | ≈74MB (Debug) | ≈54MB (Debug) | ≈66MB (Debug) | ≈98MB (Debug) | ≈24MB (Debug) | ? | ? |
| | ***MacOS*** | ≈62MB (Debug) | ≈35MB (Debug) | ≈55MB (Debug) | ≈144MB (Debug) | ≈27MB (Debug) | ? | ? |
| | ***Linux (x64)*** | ≈24MB (Debug) | ≈83MB (Debug) | ≈66MB (Debug) | ≈149MB (Debug) | ≈15MB (Debug) | ? | ? |
| **Start duration** | ***Windows (x64)*** | ≈164ms (Debug) | ? | ? | ? | ? | ? | ? |
| | ***MacOS*** | ≈277ms (Debug) | ? | ? | ? | ? | ? | ? |
| | ***Linux (x64)*** | ? | ? | ? | ? | ? | ? | ? |

# 02-empty-app-headless

See source in [benchmark/02-empty-app-headless](https://github.com/Elanis/web-to-desktop-framework-comparison/tree/main/benchmark/02-empty-app-headless/) folder.

|  |  | [Electron](https://github.com/electron/electron) | [NW.JS](https://github.com/nwjs/nw.js) | [Tauri](https://github.com/tauri-apps/tauri) | [NodeGui](https://github.com/nodegui/nodegui) | [Neutralino](https://github.com/neutralinojs/neutralinojs) | [Flutter](https://github.com/flutter/flutter) | [.Net MAUI](https://github.com/dotnet/maui) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Build size** | ***Windows (x86)*** | ≈160MB | ≈237MB | ? | ≈83MB | ≈2MB | N/A<sup>1</sup>| ? |
| | ***Windows (ARM64)*** | ≈193MB | [Requested](https://github.com/nwjs/nw.js/issues/7599) | ? | ? | ? | N/A<sup>1</sup>| ? |
| | ***Linux (x86)*** | ≈171MB | ≈329MB | ? | ? | ≈2MB | N/A<sup>1</sup>| ? |
| | ***Linux (ARMv7l)*** | ≈128MB | [Requested](https://github.com/nwjs/nw.js/issues/1151) | ? | ? | ? | N/A<sup>1</sup>| ? |
| | ***Linux (ARM64)*** | ≈196MB | [Requested](https://github.com/nwjs/nw.js/issues/1151) | ? | ? | ? | N/A<sup>1</sup>| ? |
| **Memory Usage** | ***Windows (x64)*** | ≈51MB (Debug) | ≈29MB (Debug) | ≈27MB (Debug) | ≈16MB (Debug) | ≈17MB (Debug) | N/A<sup>1</sup>| ? |
| | ***MacOS*** | ≈62MB (Debug) | ≈40MB (Debug) | ≈57MB (Debug) | ≈136MB (Debug) | ≈27MB (Debug) | N/A<sup>1</sup>| ? |
| | ***Linux (x64)*** | ≈39MB (Debug) | ≈82MB (Debug) | ≈73MB (Debug) | ≈150MB (Debug) | ≈20MB (Debug) | N/A<sup>1</sup>| ? |
| **Start duration** | ***Windows (x64)*** | ? | ? | ? | ? | ? | N/A<sup>1</sup>| ? |
| | ***MacOS*** | ≈247ms (Debug) | ? | ? | ? | ? | N/A<sup>1</sup>| ? |
| | ***Linux (x64)*** | ? | ? | ? | ? | ? | N/A<sup>1</sup>| ? |

**<sup>1</sup>**: Frameless mode not supported yet**<sup>1</sup>**: Frameless mode not supported yet


## Future content

TODO:
- WebGL Support
- Build constraints
- Source code protection
- Modules support (npm, native, etc.)

Benchmarks ideas:
 - BabylonJS scene
 - spreadsheet
 - IDE
