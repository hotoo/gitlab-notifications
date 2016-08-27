# ![logo](./assets/logo.png) GitLab Notifications

GitLab Notifications is a Google Chrome Extensions tool like GitHub Notifications.

![screen shot options](./assets/screen-shot-participating-640x400.png)


## Features

- No emails, everything in one browser, You needn't switch Applications between Mail and Browser.
- Simply and fastly.
- Multiple GitLab accounts.
- Group by Issue or MergeRequest unique key, no duplicate events.
- Direct go to the start position where your unread.
- Auto mark Issue and MergeRequest events as read when you read it.
- Immediately notify you when someone assignee or mention to you (or you alias name).
- You needn't watching the immediately notification, you can get all of events
  (include participating events) at anytime.

![screen shot options](./assets/screen-shot-watching-640x400.png)


## Installation

[Install on Chrome Web Store](https://chrome.google.com/webstore/detail/gitlab-notifications/neidmbjigjejpekbknfbmcgmkbfgmfmi)

## Configuration


1. GitLab Notifications -> Options:

    ![screen shot options](./assets/screen-shot-options-640x400.png)

1. Add Account:

    ![screen shot options](./assets/screen-shot-options-account-640x400.png)

    - `Server URL` is GitLab server url, like `https://gitlab.com`
    - `Server Name`: named you GitLab account for display.
    - `Private Token` is a secret key, from like `https://gitlab.com/profile/account`
    - `User Name` is you GitLab account username, like me is `hotoo`
    - `Alias Name`: what people called you? luck names. when people called you in issue, merge request, or note(comment),
    you will be participating this event. multiple alias name separate by comma(`,`).
    - `Notification`: choose the type for browser pop-window notification.

1. Next Step and watching projects:

    ![screen shot options](./assets/screen-shot-options-watching-640x400.png)

1. `Save`, Done. you just need quiet and waiting for notifications.

## Badge


![participating](./assets/badge-participating.gif) You have participating events, click badge icon goto the participationg event list.

![watching](./assets/badge-watching.png) You have watching events, click badge icon goto the watching event list.

![unread](./assets/badge-unread.png) You have other unread events, click badge icon goto all event list.

![read](./assets/badge-read.png) You have no unread event.

## Mark as read

1. In GitLab Notifications center, you can manually mark notifications as read.
2. In GitLab website, automatically mark notifications as read when you read a issue or merge request.


## Mark as mute

1. In GitLab Notifications center, you can mark notifications as mute.
2. In GitLab website, you can toggle notifications as mute or unmute.


## How does it works?

This extension worked base on GitLab API(v3).


## Feedback

- [User voice](./user-voice.md)
- [Find or New issue](https://github.com/hotoo/gitlab-notifications/issues)
