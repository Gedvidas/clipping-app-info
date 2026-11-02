---
layout: tiktok
title: Overview
---
# Review on your desktop. Finish in TikTok.

**Clipping by Gedvidas** is a Windows desktop application for selecting a local video, reviewing it and sending it to your TikTok Inbox. You decide whether to publish in the TikTok mobile application.

[Read the user guide](guide.html) · [Get support](support.html)

> **Availability — 2 November 2026:** the Inbox integration has been tested in TikTok Sandbox. The current production submission was not approved. Website corrections are being prepared; public production access is not available.

## What the application does

### Connect your account

TikTok Login Kit opens authorization in your browser. After authorization, the desktop application displays the connected account name. Clipping does not ask for your TikTok password.

### Review a local video

Select an MP4, MOV or WebM file and open it in your local video player. Check video and audio, then confirm that you have the rights to use it and agree to send it to the connected account.

### Confirm the transfer

A confirmation dialog shows the account, filename and duration before sending. The application checks the video and reports upload status. If a result is uncertain, check its status before repeating the upload.

### Finish in TikTok

After confirmed delivery, open the TikTok Inbox notification on your phone. Continue editing and choose whether to publish there. Sending to the Inbox is not publishing.

## Product boundaries

- This integration runs in a desktop application, not in this website.
- This website provides product documentation and support; it has no login or upload form.
- The described Inbox workflow does not use Direct Post or automatically publish videos.
- No public installer is currently offered. Contact the developer with availability questions; production access cannot be enabled through this website.

## Permissions and data

| Permission | Purpose |
| --- | --- |
| `user.info.basic` | Identify the connected account and display its name. |
| `video.upload` | Transfer a video you reviewed and approved to TikTok. |

Authorization tokens and upload records are stored in the operator's local workspace. Selected videos are sent to TikTok after confirmation. Read the [Privacy Policy](privacy.html) and [Terms of Service](terms.html).

## Help with your workflow

The [user guide](guide.html) explains connection, review, consent and delivery. The [support page](support.html) covers missing Inbox notifications, uncertain uploads and access removal.

Developer contact: [gedvidas.lapienis@gmail.com](mailto:gedvidas.lapienis@gmail.com)
