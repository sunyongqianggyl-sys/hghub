# HGhub Android ARM64 build

This repository contains a GitHub Actions workflow to build the upstream HGhub v1.2.1 Android ARM64 APK.

The workflow checks out the upstream source at the v1.2.1 tag, builds it on GitHub-hosted Ubuntu, signs the APK for installation, and uploads it as a workflow artifact.

To run: open Actions -> Build HGhub Android ARM64 -> Run workflow.

Upstream project: https://github.com/Minireel/HGhub
