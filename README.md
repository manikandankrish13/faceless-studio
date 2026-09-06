# Faceless Studio

Phone-friendly control panel for the [youtube-ideas](https://github.com/manikandankrish13/youtube-ideas) faceless
video pipeline: generate a Short or long-form video, watch it render, preview it, and upload it to YouTube.

Live at **https://manikandankrish13.github.io/faceless-studio/**

This page holds no secrets. It calls the GitHub API with a fine-grained token you paste once; the token is stored
only in your browser. Rendering and uploading run in the private repository's GitHub Actions.

Token: github.com/settings/personal-access-tokens/new -> only the `youtube-ideas` repository ->
Actions: Read and write, Contents: Read-only, Secrets: Read-only (optional).
