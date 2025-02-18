[![GitHub All Releases](https://img.shields.io/github/downloads/afkarxyz/Twitter-X-Media-Batch-Downloader/total?style=for-the-badge)](https://github.com/afkarxyz/Twitter-X-Media-Batch-Downloader/releases)

![TwitterXMediaBatchDownloader](https://github.com/user-attachments/assets/354d7470-c01c-4aa6-9da1-ea6c42d27330)

<div align="center">
<b>Twitter/X Media Batch Downloader</b> is a GUI tool that allows users to download all media, including images and videos, in their original quality from Twitter/X accounts, even withheld accounts, using <code>gallery-dl</code>
</div>

## Download

- Download the latest version of [TwitterXMediaBatchDownloader](https://github.com/afkarxyz/Twitter-X-Media-Batch-Downloader/releases/download/v1.5/TwitterXMediaBatchDownloader.exe)
- If you're familiar with **userscripts**, please install it [here](https://greasyfork.org/en/scripts/523157-twitter-x-media-batch-downloader)

## Features

- Uses the powerful `gallery-dl` library, similar to `yt-dlp`
- The ability to download media from **Withheld Accounts** _(requires unchecking the **Local** option)_
- Option to choose the media type to download: **media** (image + GIF + video) or just **image/GIF/video**
- Download images and videos in original quality
  
## Screenshots

![image](https://github.com/user-attachments/assets/085cdcee-5272-41bb-8612-06737c0ebe32)

![image](https://github.com/user-attachments/assets/3e71f14b-c4f0-4e86-87d5-9217d88cb0c2)

![image](https://github.com/user-attachments/assets/c4e086c2-d4d5-4eee-8bab-dba8e5fdd90d)

> Downloading from **Withheld Accounts**

![image](https://github.com/user-attachments/assets/f5e301cf-9700-4986-a87d-8424be40db5c)

![image](https://github.com/user-attachments/assets/92f814b1-069f-4605-b31f-8a5ff8dc0f17)

![image](https://github.com/user-attachments/assets/c6e7dc0d-659d-456e-b30c-6cca66fe9359)

## How to Obtain Auth Token

> [!Warning]
> - I suggest not using the **main account** to obtain the token.
> - You can use https://temp-mail.io to register a Twitter account.
> - Using an auth token or cookies has the potential to get the **account suspended.**
> - If too many media files are fetched, it will trigger a **rate limit**, and the media retrieval will fail.

1. Go to [Twitter's website](https://www.x.com/)
2. Log into your account
3. Open the Developer Tools by pressing `F12`
4. Navigate to the **Application** tab, then select **Storage** > **Cookies**
5. Find and copy the `auth_token` value or use the browser extension [X.com Auth Token Grabber](https://github.com/afkarxyz/Twitter-X-Media-Batch-Downloader/releases/download/v1.0/X.com.Auth.Token.Grabber.zip)
6. Do not log out of your account, as a new `auth_token` will be generated by Twitter

> X.com Auth Token Grabber

![image](https://github.com/user-attachments/assets/4bf5f787-d34f-4259-837c-07a6432c4360)

> Developer Tools

![image](https://github.com/user-attachments/assets/50f819da-7490-4f3c-b130-c5a3ee482e2d)
