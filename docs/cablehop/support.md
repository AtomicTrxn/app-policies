---
layout: default
title: CableHop Support
description: Support and troubleshooting information for CableHop
permalink: /cablehop/support/
redirect_from:
  - /macmtp/support/
---

# CableHop Support

CableHop is a macOS utility for browsing an Android device over USB using the
Media Transfer Protocol (MTP) and downloading selected files or folders.

## Before connecting

- Use macOS 14 or later.
- Unlock the Android device and choose **File transfer** or **MTP** for its USB
  connection mode.
- Use a USB cable that supports data, not a charge-only cable.
- Select a destination folder in CableHop when prompted.

## Connection troubleshooting

If the device does not appear or CableHop cannot open it:

1. Disconnect and reconnect the USB cable, then unlock the Android device.
2. Confirm that the Android USB mode is **File transfer** or **MTP**.
3. Quit other apps that may be using the device, including photo-import,
   Android file-transfer, or device-management software.
4. Try another USB port or a known data-capable cable without a hub.
5. Quit and reopen CableHop.

Only one application can normally own the Android device's MTP interface at a
time. Camera and photo-import services can sometimes claim it before CableHop.

## Transfer troubleshooting

- Confirm that the selected destination has enough free space.
- Keep the Android device unlocked and connected until the transfer finishes.
- If a transfer is interrupted, reconnect the device and use the Transfers
  workspace to review or retry it.
- macOS folder permission can be restored by selecting the destination folder
  again in CableHop.

## Diagnostics and support requests

CableHop does not send diagnostics automatically. You can copy or export a
diagnostic report from the Diagnostics workspace and choose whether to include
it with a support request.

[Open a support issue](https://github.com/AtomicTrxn/app-policies/issues/new)
and include:

- the CableHop version and macOS version;
- the Android device model and Android version;
- what you expected and what happened;
- reproducible steps and the exact error message; and
- a diagnostic report, if you are comfortable sharing it.

GitHub issues are public. Do not include file contents, credentials, device
serial numbers, private local paths, or other sensitive information. If a
request requires private details, first open an issue without those details and
ask for a private contact method.

## Privacy and local data

- [CableHop privacy policy]({{ site.baseurl }}/cablehop/privacy/)
- [Delete CableHop local data]({{ site.baseurl }}/cablehop/data-deletion/)

[Back to CableHop]({{ site.baseurl }}/cablehop/)
