---
layout: default
title: Delete MacMTP Local Data
description: How to remove local data created by MacMTP
permalink: /macmtp/data-deletion/
---

# Delete MacMTP Local Data

MacMTP does not create user accounts and does not transmit app data to the
developer or a developer-operated server. There is therefore no server-side
MacMTP account or app-data record that requires a deletion request.

MacMTP stores limited operational data locally on your Mac. You can remove it
at any time.

## Clear transfer history

Open the Transfers workspace in MacMTP and use its clear control to remove
completed, failed, cancelled, and interrupted transfer-history entries.

## Revoke folder access

You can select a different destination folder in MacMTP or revoke its access in
**System Settings > Privacy & Security > Files and Folders**. Quit MacMTP after
changing access if you want to end the current session immediately.

## Remove all MacMTP local data

To remove transfer records, preferences, saved folder permission, diagnostics,
and any remaining staging data:

1. Quit MacMTP.
2. Uninstall MacMTP from the Applications folder.
3. In Finder, choose **Go > Go to Folder** and inspect
   `~/Library/Containers/` and `~/Library/Application Support/` for an item
   belonging to MacMTP. Move that item to the Trash.
4. Empty the Trash when you are ready to remove the data permanently.

The exact sandbox-container name is based on the app's signed bundle identifier
and may differ between release channels. If you are unsure which item belongs
to MacMTP, do not delete it; [open a support issue](https://github.com/AtomicTrxn/app-policies/issues/new)
without posting sensitive information and ask for help.

Removing MacMTP data from your Mac does not delete files that you previously
downloaded to a destination folder. Delete those files separately in Finder if
you no longer want them.

## Information shared for support

If you voluntarily post information in a GitHub issue, you can edit or delete
your own content using GitHub's controls. You may also ask for removal of
information under the developer's control. GitHub processes and retains site
data under its own terms.

Apple requires in-app account deletion for apps that support account creation.
MacMTP does not support account creation, so that requirement is not applicable.
This page is provided so users can still understand and control all data MacMTP
stores locally.

- [Privacy policy]({{ site.baseurl }}/macmtp/privacy/)
- [Support]({{ site.baseurl }}/macmtp/support/)

[Back to MacMTP]({{ site.baseurl }}/macmtp/)
