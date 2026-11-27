# GDN | engineering verification without unnecessary friction

**Phase One developer preview, v0.4.5rc11. Not for production use.**

GDN is an open-source Python engineering verification tool for AI-assisted software development. It coordinates scoped engineering changes, configured checks, separate review, bounded repair and an evidence trail. It does not publish upstream changes automatically. Human approval remains mandatory.

## Distribution

Download the verified assets from [GDN Phase One v0.4.5rc11](https://github.com/timothyanderson096-ocdealcheck/gdn-standalone/releases/tag/v0.4.5rc11):

- [`GDN_0.4.5rc11_source.zip`](https://github.com/timothyanderson096-ocdealcheck/gdn-standalone/releases/download/v0.4.5rc11/GDN_0.4.5rc11_source.zip) — complete released source.
- [`gdn_standalone-0.4.5rc11-py3-none-any.whl`](https://github.com/timothyanderson096-ocdealcheck/gdn-standalone/releases/download/v0.4.5rc11/gdn_standalone-0.4.5rc11-py3-none-any.whl) — Python installation wheel.
- [`GDN_0.4.5rc11_SHA256SUMS.txt`](https://github.com/timothyanderson096-ocdealcheck/gdn-standalone/releases/download/v0.4.5rc11/GDN_0.4.5rc11_SHA256SUMS.txt) — verification checksums (also covers the separately available [release notes](GDN_0.4.5rc11_RELEASE_NOTES.md)).

The automatically generated GitHub source archives contain the repository landing-page snapshot, not the complete GDN product. Use the explicitly named source ZIP above.

 Read the source README and SECURITY.md before running GDN. The frozen RC11 passed 276 internal regression tests. The licensed repackaging retains the tested runtime. Intended-host containment, independent-model inference and comparative superiority remain unverified.

**GDN is not a security sandbox.** Real jobs require a reviewed disposable non-root Linux VM with no credentials or sensitive mounts, externally enforced resource limits and loopback-only networking. Audit evidence on a separate, clean installation. See [SECURITY.md](SECURITY.md).

## Independent evaluation

Independent technical feedback is welcome, including failed runs, reproducible defects and design critiques. Start with the documentation and safety requirements above. Share non-sensitive findings through [the public evaluation thread](https://github.com/timothyanderson096-ocdealcheck/gdn-standalone/issues/1). There is no requirement to register, endorse or star the project.

### Reproduce the verification workflow

Try the [independent verification challenge](https://github.com/timothyanderson096-ocdealcheck/gdn-standalone/issues/1): reproduce the bundled scripted demonstration, run the isolated synthetic regression suite and audit evidence on a separate clean installation. Failed reproductions are welcome. Follow the security requirements above; these exercises do not qualify real-model independence or production security.

Copyright 2026 Timothy Anderson. [Apache License 2.0](LICENSE). Free distribution, optional usage registration, no activation or telemetry. External model providers may charge separately.
