# Postman with Git

Allows Postman to use Git from the host OS for its [Native Git](https://learning.postman.com/docs/agent-mode/native-git/) feature.

Fork of https://github.com/flathub/com.getpostman.Postman

Build and deploy locally:
1. Add `flathub` repo to the user scope:
   `flatpak remote-add --if-not-exists --user flathub https://dl.flathub.org/repo/flathub.flatpakrepo`
2. Build and install locally:
   `flatpak-builder --force-clean --user --repo=repo --install build com.getpostman.Postman.yaml`