# TGDC Companion downloads

This repository exists for one reason: to host the signed installers for
**TGDC Companion** so that anyone can download them without a GitHub account.

There is no source code here. The application is built from a private
repository, signed, notarised by Apple and uploaded to the Releases page of this
repository. Installed copies update themselves from the signed feed at
`thegeneraldata.com/app/appcast.xml`.

**Get the app at [thegeneraldata.com/app](https://thegeneraldata.com/app).**
That page publishes the version, the size and the SHA-256 of each build and
links to the files below. Every release also carries a `SHA256SUMS.txt`.
Checking the hash you downloaded against the published one is the point of
publishing it.

## What the builds are signed with

| | |
|---|---|
| macOS | Developer ID Application: Levin David Schwab (R95M36AU2X), hardened runtime, notarised by Apple, ticket stapled on the app and the disk image |

TGDC Companion is a macOS app. A Windows version is not published.

## Issues

Bug reports belong in the private repository. Issues are disabled here so that
nobody files one against a repository that has no code in it.
