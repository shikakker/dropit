# DropIT — Historical Mini Storage / File-Sharing Archive

Historical file-storage / sharing product experiment described by the original README as:

```text
Your mini storage.
```

The product concept focused on browsing uploaded files, searching them quickly, opening / sharing them, and uploading common media / document types.

Historical deployment reference:

```text
https://dropit.ueuo.com/
```

Treat that URL as archival until independently confirmed to still host the intended application.

## Product concept

The old README highlights flows for:

- viewing files in a simple library;
- fast file search;
- uploading images, documents, clips, and music;
- opening files;
- sharing files with other people.

It also preserves animated GIF demonstrations for:

```text
search
drag / drop
list
open / share
```

These are useful portfolio artifacts showing the interaction model of the original storage product.

## Repository contents

The current repository does **not** contain unpacked application source code.

It currently stores release / archive bundles such as:

```text
DropIT ios pwa.zip
DropITandroidpwa.zip
DropITmetapwa.zip
README.md
LICENSE
```

There is no root:

- `package.json`;
- application source tree;
- backend service;
- database schema;
- build configuration.

Therefore this checkout should be treated as a **distribution / PWA archive**, not a reproducible source-code repository.

## PWA / packaged-app boundary

The ZIP names indicate historical PWA / packaged variants for areas such as:

```text
iOS PWA
Android PWA
meta / supporting PWA bundle
```

Without unpacked source and build metadata, this repository alone cannot establish:

- the PWA framework used;
- service-worker behavior;
- offline caching strategy;
- backend storage provider;
- authentication model;
- upload limits;
- sharing-token security;
- file-retention behavior.

Do not infer these technical properties from the archive names alone.

## Reproducibility gap

A maintainable storage product repository should ideally preserve:

```text
frontend source
backend / API source
storage integration
manifest / service worker
build configuration
lockfile
schema / migrations
environment example
README setup
```

The current ZIP-based archive cannot be reviewed or rebuilt normally through Git.

If DropIT remains portfolio-relevant, extract the canonical source version into a dedicated repository rather than keeping ZIP files as the only implementation artifact.

## File-storage security boundary

A real file-sharing product needs explicit controls for:

- user authentication;
- file ownership;
- object-storage authorization;
- share-link entropy / expiry;
- private vs public files;
- upload MIME / size validation;
- malware scanning where appropriate;
- filename / path handling;
- download authorization;
- deletion / retention;
- quota enforcement;
- abuse / copyright reporting;
- audit / access logs.

The current archive does not provide enough source material to verify these areas.

## Privacy

Files uploaded to a storage product can contain highly sensitive personal or business data.

A modern deployment should document:

- where files are stored;
- encryption in transit / at rest;
- who can access them;
- how long they are retained;
- how deletion works;
- whether share links can be revoked;
- whether analytics / third parties receive file metadata.

## Portfolio use

DropIT is useful as historical product / UX evidence around:

- cloud-storage information architecture;
- file upload;
- drag-and-drop interaction;
- search;
- file libraries;
- open / share flows;
- PWA packaging experiments.

It should not be presented as a currently maintainable storage SaaS unless the original source / backend is restored.

## Current status

**Historical PWA / file-storage distribution archive.** Product demos and packaged ZIP artifacts are preserved; unpacked source and backend architecture are not present in the current repository.

## License

The repository contains a **CC0 1.0 Universal** dedication. Verify whether that dedication was intended to cover every bundled binary / third-party asset inside the ZIP files before relying on it for redistribution.