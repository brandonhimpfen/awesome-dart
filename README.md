# Awesome Dart [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for Dart, server-side Dart frameworks, web engines, database drivers, state management libraries, code generation toolkits, and FFI interop.

Dart is a client-optimized, object-oriented, strongly typed language developed by Google. Engineered for multi-platform development across mobile, web, desktop, and backend systems, it features sound null safety, isolate-based concurrency, Ahead-Of-Time (AOT) compilation to native code, and Just-In-Time (JIT) execution with hot reload. This list is intended for mobile developers, backend engineers, web developers, and system architects building with Dart.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Server-Side & Web Frameworks](#server-side--web-frameworks)
- [Databases & Persistence](#databases--persistence)
- [Code Generation & Metaprogramming](#code-generation--metaprogramming)
- [Asynchronous & Native Interop](#asynchronous--native-interop)
  - [Concurrency & Async Utilities](#concurrency--async-utilities)
  - [Foreign Function Interface (FFI)](#foreign-function-interface-ffi)
- [Related Awesome Lists](#related-awesome-lists)

## Server-Side & Web Frameworks

HTTP servers, REST API micro-frameworks, static site generators, and web rendering engines built in pure Dart.

- [Dart Frog](https://github.com/dart-frog-dev/dart_frog) — Fast, minimalistic backend framework for Dart designed to optimize developer experience and route composition.
- [Jaspr](https://github.com/schultek/jaspr) — Modern web framework for building websites in Dart supporting Single Page Applications (SPA), Server-Side Rendering (SSR), and Static Site Generation (SSG).
- [Alfred](https://github.com/rrousselGit/alfred) — Minimal ExpressJS-inspired HTTP server framework with intuitive routing and middleware support.
- [Rikulo Stream](https://github.com/rikulo/stream) — Lightweight web server featuring request routing, filters, template engines, and WebSocket integrations.

## Databases & Persistence

Embedded NoSQL key-value stores, object databases, reactive SQLite wrappers, and PostgreSQL drivers.

- [Hive](https://github.com/isar/hive) — Lightweight, high-performance, key-value database written in pure Dart for local persistence.
- [Isar](https://github.com/isar/isar) — Ultra-fast, feature-rich NoSQL database for Dart with full ACID support and cross-platform query filters.
- [ObjectBox](https://github.com/objectbox/objectbox-dart) — Super-fast object-relational database for Dart providing lightweight persistence and vector search capabilities.
- [Drift](https://github.com/simolus3/drift) — Reactive, type-safe persistence library for SQLite written in Dart, offering fluent query builders and migrations.
- [Postgres](https://github.com/isoos/postgresql-dart) — High-performance PostgreSQL driver implementing the extended binary protocol for secure, efficient queries.

## Code Generation & Metaprogramming

Build systems, AST generators, serialization frameworks, and template engines.

- [build_runner](https://github.com/dart-lang/build) — Standard build system and file generator for Dart projects powering code generation pipelines.
- [source_gen](https://github.com/dart-lang/source_gen) — Automated source code generation framework built on top of the Dart analyzer and build system.
- [freezed](https://github.com/rrousselGit/freezed) — Code generator for data classes, union types, pattern matching, and JSON serialization.
- [mason](https://github.com/felangel/mason) — Template generator engine allowing developers to create, distribute, and consume reusable code bricks.
- [json_serializable](https://github.com/google/json_serializable.dart) — Automated builder for generating JSON serialization and deserialization boilerplate.

## Asynchronous & Native Interop

Utilities for handling event streams, isolate management, C/C++ native bindings, and WebAssembly bindings.

### Concurrency & Async Utilities

- [package:async](https://github.com/dart-lang/async) — Core utility package extending standard `Future` and `Stream` operations for advanced asynchronous patterns.
- [rxdart](https://github.com/ReactiveX/rxdart) — ReactiveX implementation for Dart extending standard `StreamController` streams with reactive operators.
- [isolate_manager](https://github.com/tuanpmt/isolate_manager) — Multithreading library for executing heavy background tasks seamlessly using Dart isolates.

### Foreign Function Interface (FFI)

- [dart:ffi](https://dart.dev/guides/libraries/c-interop) — Core native interop interface allowing Dart programs to call native C APIs directly.
- [ffigen](https://github.com/dart-lang/ffigen) — Bindings generator that converts C header files (`.h`) directly into type-safe `dart:ffi` bindings.
- [flutter_rust_bridge](https://github.com/fzyzcjy/flutter_rust_bridge) — High-performance binding generator facilitating seamless memory-safe interop between Dart and Rust.

## Related Awesome Lists

- [Awesome Functional Programming](https://github.com/brandonhimpfen/awesome-functional-programming) — Purely functional concepts, immutability, type systems, and lambda calculus.
- [Awesome Java](https://github.com/brandonhimpfen/awesome-java) — High-performance JVM libraries, concurrency toolkits, and object-oriented frameworks.
- [Awesome JavaScript](https://github.com/brandonhimpfen/awesome-javascript) — JS runtimes, asynchronous patterns, bundlers, and web engines.
- [Awesome Open Source](https://github.com/brandonhimpfen/awesome-open-source) — Guidelines, licensing models, and project governance for open software repositories.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
