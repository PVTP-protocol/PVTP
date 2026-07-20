# Overview

PVTP sits between a client and a server.

Typical flow:
1. Client requests a visual resource.
2. Server returns metadata and a preview layer.
3. Client renders immediately.
4. Server continues sending higher-quality data.
5. Client upgrades the visual asset progressively.

This gives users a better experience on slow or unstable networks.
