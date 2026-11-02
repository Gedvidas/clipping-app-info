---
layout: tiktok
title: User guide
---
# User guide

This guide describes the existing Windows desktop Inbox workflow. Production access is not approved. Testing is limited to the configured TikTok Sandbox and its authorized testers.

## Before you start

Use a Windows computer with the desktop application configured by the operator, a local video player and a video you have permission to upload. The application uses FFmpeg's `ffprobe` to inspect the file. You also need access to the same TikTok account on your phone.

There is currently no public installer. Contact [support](support.html) for availability information. Do not enter developer credentials into this website.

## 1. Open and connect

Open the configured application using `Clipping.cmd`. Choose **Prisijungti per TikTok** (Sign in through TikTok). Complete TikTok authorization in your browser and return to the desktop window. Check the account name shown there.

TikTok handles your sign-in. Clipping requests `user.info.basic` and `video.upload` for account identification and transfer to the Inbox.

## 2. Select and review

Choose **Pasirinkti video** (Select video), then **Peržiūrėti video** (Preview video). Watch the file in your local player and check its picture and sound. Supported file selections are MP4, MOV and WebM; media is checked before sending.

## 3. Give consent

Select the consent checkbox only if you have the necessary rights and want to send the video. Choose **Siųsti į TikTok juodraščius** (Send to TikTok drafts). The final confirmation shows the account, filename and duration. Confirm to begin the transfer, or cancel without sending.

## 4. Check delivery

Wait for the application status. Confirmed delivery to TikTok Inbox means you can continue in TikTok. A timeout does not prove that the transfer failed. Read [upload troubleshooting](support.html#upload-status-is-uncertain) before trying again.

## 5. Finish on your phone

Open TikTok with the same account and find the Inbox notification for the upload. Continue editing. Review the final video, caption and publishing options in TikTok. Publication remains your decision.

## Disconnect or request deletion

Revoke the application's access in TikTok account settings. For locally stored information, contact the operator as described in the [Privacy Policy](privacy.html#retention-and-deletion). Deleting local records does not delete content already held by TikTok.
