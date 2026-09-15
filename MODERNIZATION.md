# DropIT — Preservation & Recovery Roadmap

The repository is currently a distribution/PWA archive rather than a reproducible source repository.

## 10 tasks

1. Preserve the existing ZIP bundles and record checksums/provenance before unpacking.
2. Extract the archived bundles into a separate recovery branch or directory for inspection.
3. Identify the original frontend framework, service worker, manifest and storage/backend assumptions from recovered source.
4. Recover the canonical source tree and dependency manifests if present inside the archives.
5. Verify whether historical upload/search/share flows were client-only or depended on a remote backend.
6. Audit any recovered endpoints, credentials, analytics and third-party storage configuration before running the app.
7. Add a modern `.gitignore`, dependency lock strategy and reproducible local setup once source is recovered.
8. Capture portfolio-quality screenshots/GIFs of search, drag/drop, list and sharing flows before modernization changes.
9. Clearly separate historical product behavior from features that cannot be verified from the current archive.
10. Use DropIT as a historical PWA/file-product case only after provenance and source recovery are documented.

## Portfolio value

Good historical interaction/product evidence; weak engineering evidence until unpacked source and build steps are recovered.