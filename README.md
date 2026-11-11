# Stock Starlight Sandbox

Source for the [sandbox](https://stockstarlight.sandbox.discussionbridge.dev/). This stock Starlight site serves as the control for the Astro adapter sandbox.

The source uses Starlight and Astro. The paired [Astro and Starlight sandbox](https://astrostarlight.sandbox.discussionbridge.dev/)
is where the DiscussionBridge integration is exercised.

## Local commands

```sh
npm ci
npm run dev
npm run build
npm run deploy:dry-run
```

Cloudflare Workers serves the generated site. Keep connection secrets in
protected configuration. Record the package and commit used by a test build.

[Sandbox chooser](https://sandbox.discussionbridge.dev/) · [Starlight documentation](https://starlight.astro.build/)
