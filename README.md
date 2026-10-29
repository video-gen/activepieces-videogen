# VideoGen

[VideoGen](https://videogen.io/) creates editable videos through a developer API. This piece starts a storyboard workflow with high quality, captions, image animation and automatic export; reads its status/downloadUrl; reads account details; and supports a custom API call.

Create an API key at https://app.videogen.io/api. Starting generation spends credits and requires the approval checkbox. Map workflowRunId into Get Video Status and repeat only the read step to poll. Do not repeat Start Storyboard Video to resume waiting.

[API documentation](https://docs.videogen.io/) · [MCP setup](https://videogen.io/videogen-mcp)

Contributed by VideoGen with AI assistance. No paid generation was executed for this contribution.

## Install

In Activepieces, open Settings → My Pieces → Install Piece and enter `@videogen/piece-videogen`. Availability of custom/community pieces depends on your deployment. This package is maintained independently by VideoGen; it is not bundled with the official Activepieces catalog.

## Build provenance

Built with Activepieces commit 6e52092eee5a037b05d44e10e7d4e28d9b6af0d5. The source actions are in `src/`. The shipped `dist/src/index.js` is a self-contained bundle produced by upstream `preparePieceDistForPublish`, which inlines the framework/common libraries and runs its bundle safety gate. The upstream MIT license is included.

Checks: scoped TypeScript build and ESLint, four mocked action tests, bundle safety gate and standalone import/action metadata checks. No paid generation was executed.
