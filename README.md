# ![logo](./assets/logo.png) GitLab Notifications

GitLab Notifications is a Google Chrome Extensions tool like GitHub Notifications.

![screen shot options](./assets/screen-shot-participating-640x400.png)


## Features

- No emails, everything in one browser, You need't switch Applications between Mail and Browser.
- Simply and fastly.
- Multiple GitLab accounts.
- Group by Issue or MergeRequest unique key, no duplicate events.
- Direct go to the start position where your unread.
- Auto mark Issue and MergeRequest events as read when you read it.
- Immediately notify you when someone assignee or mention to you (or your alias name).
- You need't watching the immediately notification, you can get all of events
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
    - `Server Name`: named your GitLab account for display.
    - `Private Token` is a secret key, from like `https://gitlab.com/profile/account`
    - `User Name` is your GitLab account username, like me is `hotoo`
    - `Alias Name`: what people called you? luck names. when people called you in issue, merge request, or note(comment),
    you will be participating this event. multiple alias name separate by comma(`,`).
    - `Notification`: choose the type for browser pop-window notification.
        - `Watching`: All of your watching projects events (Issues, Merge Requests, Comments) will popup notification you.
        - `Participating`: All of your participating events will popup notification you.
        - `Disable`: Disable popup notification.

        ![screen shot popup notification](./assets/screen-shot-pop-notification.png)

1. Next Step and watching projects:

    ![screen shot options watching](./assets/screen-shot-options-watching-640x400.png)

1. `Save`, Done. you just quiet and waiting for notifications.

## Badge

![participating](./assets/badge-participating.png) You have participating events, click badge icon goto the participationg event list.

![watching](./assets/badge-watching.gif) You have watching events, click badge icon goto the watching event list.

![unread](./assets/badge-unread.png) You have other unread events, click badge icon goto all event list.

![read](./assets/badge-read.png) You have no unread event.


## Event Status

![issue-opened](./assets/status-issue-opened.png) Issue is opened.

![issue-closed](./assets/status-issue-closed.png) Issue is closed.

![issue-unknow-status](./assets/status-issue-unknow.png) Unknow issue status.

![MR-opened](./assets/status-mr-opened.png) Merge Request is opened.

![MR-accepted](./assets/status-mr-accepted.png) Merge Request is accepted.

![MR-closed](./assets/status-mr-closed.png) Merge Request is closed.

![MR-unknow-status](./assets/status-mr-unknow.png) Unknow merge request status.


## Mark as read

1. In GitLab Notifications center, you can manually mark notifications as read.
2. In GitLab website, automatically mark notifications as read when you read a issue or merge request.


## Mark as mute

1. In GitLab Notifications center, you can mark notifications as mute.
2. In GitLab website, you can toggle notifications as mute or unmute.

![Mark as mute](./assets/mark-as-mute.png)

![Mark as unmute](./assets/mark-as-unmute.png)


## How does it works?

This extension worked base on GitLab API(v3).


## Bad news

- This extension just support Google Chrome web browser now.
- Your notifications data store on your web browser. When you use multiple browser profiles or different devices,
  and the profiles or devices use the same GitLab accounts, you will be get duplicate notifications.

## Support this extension

- [Star this repository](https://github.com/hotoo/gitlab-notifications)
- [Review on Chrome Web Store](https://chrome.google.com/webstore/detail/gitlab-notifications/neidmbjigjejpekbknfbmcgmkbfgmfmi/reviews)


## Feedback

- [User voice](./user-voice.md)
- [Find or New issue](https://github.com/hotoo/gitlab-notifications/issues)
