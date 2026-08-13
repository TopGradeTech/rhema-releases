# Rhema Releases — retired

> **This repository is archived. Rhema now lives at
> [TopGradeTech/rhema](https://github.com/TopGradeTech/rhema).**
>
> **[Download the latest release](https://github.com/TopGradeTech/rhema/releases/latest)**

This repo held only release builds of Rhema — never source code. It existed
because the source repository was private, while the app's in-app "Check for
Updates" still needed to query a public Releases API without authentication.

The source repository is now public, so code, issues, discussions, and
releases all live in one place and this split is no longer needed. Releases
here stop at **v1.1.4**; everything from **v1.1.5** onward is published on the
main repository.

## If you are running Rhema v1.1.4 or earlier

Those versions check *this* repository for updates, so they will not find
newer releases automatically. To reconnect:

1. Download `Rhema-Setup.exe` from the
   [latest release on the new repository](https://github.com/TopGradeTech/rhema/releases/latest).
2. Run it once over your existing installation. Your settings are preserved.

After that, automatic updates work normally and no further manual steps are
needed.

## Why this repo is kept rather than deleted

The historical installers attached to the releases here remain downloadable,
so existing download links keep working and older versions stay available for
rollback. Nothing new will be published here.
