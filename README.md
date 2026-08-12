# DockRoute — Unraid Community Applications templates

Container templates for [Unraid](https://unraid.net/)'s
[Community Applications](https://forums.unraid.net/topic/38582-plug-in-community-applications/)
plugin.

- **[dockroute.xml](dockroute.xml)** — [DockRoute](https://github.com/Dockroute/Dockroute):
  External-DNS for plain Docker hosts. Watches running containers, reads
  `dockroute.*` labels and reconciles the matching DNS records — and
  Cloudflare Tunnel routes — in a pluggable provider. TXT-based ownership
  means it never alters records it cannot prove it manages.

The canonical template source lives in the main repo under
[`templates/unraid/`](https://github.com/Dockroute/Dockroute/tree/main/templates/unraid);
this repository is the copy Community Applications indexes.
