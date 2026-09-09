<p align="center">
  <img src="./assets/misty-full.png" alt="Misty" width="500">
</p>

Misty is a modern file manager for working across local files, cloud drives, object storage, and backups. It makes remote files feel close at hand, with fast browsing, unified search, reliable background transfers, custom plugin workflows, and privacy-conscious defaults that let the app grow around the way you work.

## Built With

Misty builds on excellent open-source tools, including:

- [rclone](https://rclone.org/) for cloud storage connectivity.
- [restic](https://restic.net/) for encrypted backups.
- [imgui](https://github.com/ocornut/imgui) for fast, flexible native interface tooling.

## What's Public

Public repositories include work that benefits from being easy to inspect, use, or contribute to:

- `misty-plugins`: public plugin interfaces, examples, and community-facing extension points.
- `misty-setup`: the public installer and setup flow for getting Misty running on a device.
- `misty-website`: the public website for Misty.
- `misty-docs`: documentation, guides, and reference material for using and extending Misty.

## What's Private

Private repositories include the core product, backend services, and infrastructure-sensitive code:

- The main file manager application and product implementation.
- Backend services, internal APIs, accounts, licensing, and release infrastructure.
- Networking, routing, and deployment-adjacent infrastructure.

These stay private to protect user data, keep security-sensitive implementation details out of public view, and preserve product direction while Misty is still changing quickly.
