---
layout: page
title: Application security with evidence
---

We build open-source security tools and help teams use them well. A security answer should carry its evidence with it: what a release contains, which weaknesses are real, and what is actually reachable in your code.

## Projects

### [chen](https://github.com/AppThreat/chen)

A code analysis library that turns a program into one queryable graph of syntax, control flow, and data movement, so "can untrusted input reach this call" becomes a question with a provable answer.

### [atom](https://github.com/AppThreat/atom)

Turns a Java, Python, JavaScript, TypeScript, PHP, Ruby, Scala, or C/C++ codebase into a compact, queryable file with call relationships and data flows. cdxgen uses it to prove which dependencies a program actually uses.

### [chennai](https://github.com/AppThreat/chennai)

A terminal application for exploring source and binaries, with an optional AI agent that must prove every finding with a real data-flow path before reporting it. Runs fully offline on your machine.

## Toolchains

### [cdxgen](https://github.com/cdxgen/cdxgen)

A complete software transparency toolchain: inventories for applications, containers, and operating systems, CycloneDX bills for components and cryptography, VEX documents, and signed, attestable output. Extended by [cdxgen-plugins-bin](https://github.com/cdxgen/cdxgen-plugins-bin) with the golem, rusi, and kosi data-flow and reachability slicers, [caxa](https://github.com/cdxgen/caxa) standalone packaging, and [safer-exec](https://github.com/cdxgen/safer-exec) runtime tracing.

### [blint](https://github.com/owasp-dep-scan/blint)

Binary analysis for reverse engineers and security analysts: what an executable, APK, or IPA contains and can do, without running it. Helped by [multi-demangle](https://github.com/AppThreat/multi-demangle) for symbol recovery and [blint-db](https://github.com/AppThreat/blint-db) for identifying components in stripped binaries.

### [dep-scan](https://github.com/owasp-dep-scan/dep-scan)

Audits dependencies for vulnerabilities and license conflicts and ranks them by risk, powered by the offline [vulnerability-db](https://github.com/AppThreat/vulnerability-db).

### [dosai](https://github.com/owasp-dep-scan/dosai)

Code-level evidence for .NET: methods, call graphs, taint analysis, crypto inventory, and API endpoints from source, assemblies, or NuGet packages.

## Services

- Custom security tool development
- Architecture reviews and security assessments
- Product security risk assessments
- Training in code analysis and secure coding

## Contact

Write to [hello@appthreat.com](mailto:hello@appthreat.com) or visit our [GitHub](https://github.com/AppThreat).
