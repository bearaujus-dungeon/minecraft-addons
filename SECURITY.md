# Security Policy

## Supported Versions

Security reports are accepted only for currently published Bearaujus addon versions and supported Minecraft versions.

Minimum supported Minecraft version: `26.1.2`.

## Reporting A Vulnerability

Do not publicly disclose exploit details in an issue.

Preferred flow:

1. Use GitHub private vulnerability reporting if it is enabled for this repository.
2. If private reporting is not enabled, open a minimal issue using the "Security contact request" template.
3. Do not include exploit steps, private logs, tokens, server addresses, or proof-of-concept files in a public issue.

The maintainer will provide a private contact path when available.

For initial contact, email haryo.assyafah@gmail.com with a brief safe summary.

## Scope

In scope:

- remote code execution risks caused by an addon
- malicious file write/read behavior caused by an addon
- privilege bypass in addon commands or networking
- crashes or denial-of-service that can be triggered by normal players
- private data leakage caused by an addon

Out of scope:

- vulnerabilities in Minecraft, Java, Fabric, Modrinth, launchers, or unrelated third-party mods
- reports for modified or reuploaded builds
- social engineering
- issues requiring unsupported Minecraft versions
