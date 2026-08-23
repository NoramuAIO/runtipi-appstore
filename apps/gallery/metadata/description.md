## Self-hosted photo and video management with shared spaces and smart search.

Noodle Gallery is a community fork of [Immich](https://github.com/immich-app/immich). It keeps everything Immich does — mobile auto-backup, timeline, albums, face recognition, natural-language search — and adds features built on top:

- **Shared spaces** — a shared library for a household or a group, with per-member roles, shared people and shared albums
- **Smart search & dynamic filters** — filter the timeline by anything in your metadata, and click a value in the viewer to filter by it
- **User groups** — manage access for several people at once
- **S3-compatible storage** — keep originals on object storage instead of local disk
- **Auto-classification and pet detection** — tag photos automatically, and recognise pets alongside people
- **Image editing and video trimming** — crop, rotate and adjust without leaving the app

Native apps are available on the [App Store](https://apps.apple.com/us/app/noodle-gallery/id6761776289) and [Google Play](https://play.google.com/store/apps/details?id=de.opennoodle.gallery).

Documentation: [docs.opennoodle.de](https://docs.opennoodle.de)

> [!NOTE]
> Machine learning (search, face and pet recognition) runs in the `gallery-ml` container and downloads its models on first use. Expect the first indexing run to take a while, and give the app a few GB of RAM.
