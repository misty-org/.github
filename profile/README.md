<p align="center">
  <img src="./assets/misty-full.png" alt="Misty" width="300">
</p>

Misty is a modern file manager for working across local files, cloud drives, object storage, and backups. It makes remote files feel local with fast browsing, unified search, and reliable background transfers. Unlike traditional file managers, Misty supports custom plugin workflows for automating repetitive tasks, adding specialized tools, and shaping the app around the way you work. The goal is to give everyone one place to manage their files, no matter where those files live.

## Built With

Misty builds on excellent open-source tools, including:
- [rclone](https://rclone.org/) for secure, cloud storage connectivity.
- [restic](https://restic.net/) for encrypted, reliable backups.
- [imgui](https://github.com/ocornut/imgui) for fast, flexible native interface tooling.

Huge thanks to the maintainers and contributors behind these projects. Misty would not be possible without their work.

## What's Public

Public repositories include work that benefits from being easy to inspect, use, or contribute to:

- `misty-plugins`: public plugin interfaces, examples, and community-facing extension points.
- `misty-setup`: the public installer and setup flow for getting Misty running on a device.
- `misty-docs`: documentation, guides, and reference material for using and extending Misty.

## What's Private

Private repositories include the core product, backend services, and infrastructure-sensitive code:

- The main file manager application and product implementation.
- Backend services, internal APIs, accounts, licensing, and release infrastructure.
- Networking, routing, and deployment-adjacent infrastructure.


These stay private to protect user data, keep security-sensitive implementation details out of public view, and preserve product direction while Misty is still changing quickly.
