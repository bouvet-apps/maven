# Bouvet Apps Maven Repository

This public repository hosts releases of Bouvet applications in Maven directory
layout. Application source code is maintained in the individual
[bouvet-apps repositories](https://github.com/bouvet-apps).

## Downloading an application

Artifacts are arranged by group, artifact and version:

```text
<group-path>/<artifact-id>/<version>/<artifact-id>-<version>.jar
```

The download URL follows this pattern:

```text
https://github.com/bouvet-apps/maven/raw/main/<group-path>/<artifact-id>/<version>/<artifact-id>-<version>.jar
```

Replace `<group-path>` with the group ID using slashes instead of dots, and use
the published artifact ID and version for the other placeholders.
Downloads from this public repository do not require authentication.

## Publishing

Releases should be stored under their versioned paths together with their Maven
metadata. Publishing changes to this repository requires GitHub write access.
Release automation can be configured in the individual application repositories.
