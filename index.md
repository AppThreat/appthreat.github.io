---
layout: page
title: Proof, not noise
---

Everything we build serves two tools. [chennai](https://github.com/AppThreat/chennai) proves what your code and binaries actually do. [dep-scan](https://github.com/owasp-dep-scan/dep-scan) audits what your software is built from. The rest of our projects are toolkits for these two.

## chennai

The orchestrator for code and binary analysis. Point it at a repository or an executable and explore methods, calls, and data flows from the terminal. Its optional AI agent must prove every finding with a real data-flow path before reporting it, and it runs fully offline.

- [atom](https://github.com/AppThreat/atom) turns Java, Python, JavaScript, TypeScript, PHP, Ruby, Scala, or C/C++ code into a compact, queryable graph, built on the [chen](https://github.com/AppThreat/chen) analysis library.
- [blint](https://github.com/owasp-dep-scan/blint) reads executables, WebAssembly, Android, and iOS apps without running them, aided by [multi-demangle](https://github.com/AppThreat/multi-demangle) for symbol recovery and [blint-db](https://github.com/AppThreat/blint-db) for identifying components in stripped binaries.
- [dosai](https://github.com/owasp-dep-scan/dosai) brings the same evidence to .NET, from source, assemblies, or NuGet packages.

## dep-scan

The orchestrator for dependency risk. It inventories your project or container image, checks every component against known vulnerabilities and license conflicts, and ranks the results by risk, with no network access needed.

- [cdxgen](https://github.com/cdxgen/cdxgen) is the software transparency toolchain behind the inventory: bills of materials for applications, containers, and operating systems, crypto bills, VEX documents, and signed, attestable output.
- [cdxgen-plugins-bin](https://github.com/cdxgen/cdxgen-plugins-bin) extends it with the golem, rusi, and kosi data-flow and reachability slicers for Go, Rust, and Kotlin.
- [caxa](https://github.com/cdxgen/caxa) packages everything into standalone executables, and [safer-exec](https://github.com/cdxgen/safer-exec) turns observed runtime behavior into a bill of materials.
- [vulnerability-db](https://github.com/AppThreat/vulnerability-db) merges NVD, OSV, GitHub, and Linux distribution advisories into one offline, open-format database.

## Services

- Custom security tool development
- Architecture reviews and security assessments
- Product security risk assessments
- Training in code analysis and secure coding

## Contact

Write to [hello@appthreat.com](mailto:hello@appthreat.com) or visit our [GitHub](https://github.com/AppThreat).
