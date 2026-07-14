---
layout: default
title: MacMTP Privacy Policy
description: Privacy policy for the MacMTP macOS application
permalink: /macmtp/privacy/
---

# MacMTP Privacy Policy

**Effective date:** July 14, 2026

**Developer:** Tom Hess

This Privacy Policy explains how MacMTP handles information when you use the
MacMTP application for macOS. The Mac App Store version of MacMTP lets you
browse an Android device connected by USB using the Media Transfer Protocol
(MTP) and download selected files or folders to your Mac. It does not modify
content on the Android device.

## Summary

MacMTP does not transmit your files, file contents, device information, usage
information, diagnostics, or other personal data to the developer or to a
developer-operated server. MacMTP does not use advertising, analytics,
tracking, or third-party data-collection SDKs. It does not create user accounts
or sell, rent, or share personal data.

MacMTP processes the information needed to browse and transfer files locally on
your Mac and connected Android device. Some operational information is stored
locally so the app can show transfer status, recover safely from interruptions,
and provide diagnostics.

## Information processed on your devices

MacMTP may access or process the following information locally when you use its
features:

- File and folder names, paths, sizes, modification dates, storage identifiers,
  and other MTP metadata from the connected Android device.
- The contents of files or folders you explicitly choose to download.
- Basic USB and device information needed to establish and diagnose an MTP
  connection, such as manufacturer, model, device software version, USB
  identifiers, connection speed, and whether a device serial number is present.
  MacMTP redacts the serial-number value from its diagnostics summary.
- The Mac folder you select and a macOS security-scoped bookmark that allows
  MacMTP to restore access to that folder on a later launch.
- Transfer records, which may include remote file or folder names, local paths,
  object and storage identifiers, byte counts, timestamps, operation status,
  and error details.
- Bounded diagnostic event history containing app, USB, MTP session, and
  transfer events. Phone file or folder names may appear when needed to explain
  an operation. File contents are not included, and recognized local filesystem
  paths are redacted from diagnostic history and exported diagnostic reports.

This processing occurs locally. Connecting a device or selecting a folder does
not send this information to the developer.

## Local storage and retention

MacMTP stores operational data in its macOS Application Support directory and,
for the Mac App Store version, within its sandbox container. This may include:

- A transfer journal used for progress, interruption safety, and manual retry.
- A diagnostic history limited to approximately 1,000 lines and 256 KB.
- Temporary staging files used to publish downloads safely after transfer.
- App preferences and the security-scoped bookmark for the Mac folder you
  selected.

Completed, failed, cancelled, and interrupted transfer records are limited to
the 200 most recently updated terminal records. Non-terminal records are
retained until MacMTP can record a safe terminal state. Temporary files are
retained only as needed to complete or clean up a transfer. The selected-folder
bookmark remains until it is replaced, becomes invalid, or the app's local data
is removed.

## Your choices and deletion

You control which Android device is connected, which Mac folder MacMTP may use,
and which files or folders are transferred. You can disconnect the Android
device at any time. You can revoke MacMTP's access to files and folders in macOS
System Settings, select a different folder in MacMTP, or remove the app's local
container and Application Support data after quitting the app.

The Transfers workspace includes a control to clear completed and other
terminal transfer-history entries. To remove all MacMTP local records,
preferences, bookmarks, diagnostics, and staging data, follow the
[local-data deletion instructions]({{ site.baseurl }}/macmtp/data-deletion/).

Because MacMTP does not transmit app data to the developer, the developer does
not maintain a server-side MacMTP account or app-data record to access, export,
or delete.

## Diagnostics and support you choose to share

MacMTP does not send diagnostics automatically. The app lets you copy or export
a diagnostic report. Nothing is shared unless you take an additional action,
such as attaching that report to a support request.

Support is provided through the
[public support issue tracker](https://github.com/AtomicTrxn/app-policies/issues).
GitHub issues are generally public. Do not post file contents, unredacted local
paths, device serial numbers, credentials, or other sensitive information. If
you voluntarily submit information through GitHub, GitHub processes that
information under its own privacy terms, and it remains subject to GitHub's
retention and deletion controls. You may edit or delete content where GitHub
allows, or contact the developer through the issue tracker for help with
content under the developer's control.

The developer uses information you voluntarily provide for support only to
respond to your request, diagnose problems, maintain app safety, and improve
MacMTP. The developer does not sell that information or use it for advertising
or user profiling. A support submission is retained for as long as the GitHub
issue or discussion remains available or as otherwise required to resolve and
document the request. You may use GitHub's controls to edit or delete your
submission, or request removal of information under the developer's control.

## Sharing, tracking, and third parties

MacMTP does not share app data with advertisers, data brokers, analytics
providers, or other third parties. It does not track you across apps or
websites, and it does not display advertising.

MacMTP includes the open-source `libusb` library to communicate with USB
devices. That library operates locally and is not an analytics or
data-collection service.

Apple processes App Store downloads, purchases, updates, and any system-level
analytics or crash information you choose to share under Apple's own privacy
terms. Those services are operated by Apple and are separate from data
processing performed by MacMTP.

## Privacy-policy website

This policy is hosted using GitHub Pages. When you visit this webpage, GitHub
may process technical information such as your IP address and browser request
under the
[GitHub General Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
MacMTP does not add advertising or analytics scripts to this page.

## Children

MacMTP is a general-purpose file-transfer utility and is not directed to
children. The app does not knowingly collect personal information from
children or from any other user.

## Security

MacMTP uses the macOS App Sandbox, user-selected file access, and local app
storage to limit access to information used by the app. No security measure can
guarantee absolute protection, so you should keep macOS up to date and avoid
sharing exported diagnostics or files with people you do not trust.

## Changes to this policy

This policy may be updated when MacMTP's features or data practices change. The
effective date at the top of this page will be revised when an update is
published. Any App Store privacy disclosures will also be updated when
required.

## Contact

For privacy questions or requests, open an issue in the
[public support issue tracker](https://github.com/AtomicTrxn/app-policies/issues/new).
Because issues may be public, describe the request without including sensitive
information and ask for a private contact method if one is needed.

- [Support]({{ site.baseurl }}/macmtp/support/)
- [Delete local app data]({{ site.baseurl }}/macmtp/data-deletion/)

[Back to MacMTP]({{ site.baseurl }}/macmtp/)
