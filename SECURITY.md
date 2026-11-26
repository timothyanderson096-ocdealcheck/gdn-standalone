# Security policy

GDN 0.4.5rc11 is a developer preview, not a security sandbox or a production-qualified product. Model-generated code and operator-approved commands can execute with the job account's permissions before human review. Use a reviewed disposable non-root Linux VM with no credentials or sensitive mounts, externally enforced CPU, memory, disk and process limits, and no networking beyond loopback. Prepare approved dependencies before execution. Do not rely on doctor, process lifetime controls or the limited fixture isolation as proof of general containment. Audit on an independently hash-verified installation in a clean environment that has never run the job or untrusted code. Human approval is required before publishing candidate changes.

Use the full SECURITY.md in the source release for additional requirements and limitations. Intended-host containment and independent-model inference have not been qualified.

Report security concerns privately via [GitHub security advisories](https://github.com/timothyanderson096-ocdealcheck/gdn-standalone/security/advisories/new) once private vulnerability reporting is enabled. Do not post vulnerability details, private evidence or credentials in public issues. Enable and monitor private reporting before distributing release assets. No response-time guarantee is made.
