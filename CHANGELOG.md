## Unreleased
### Added
- Added basic ability to post to a community with Markdown
- Added basic ability to create a comment in a post
- Added settings option to enable or disable the in-app update notifications
- Added the instance name to various parts of the app to distinguish communities across instances
- Added blur to NSFW images - contribution from @guigs4
- Added fastlane config for Android - contribution from @IzzySoft
- Initial support for opening links for lemmy communities within the app rather than through the browser
- Added community information when opening up a community
- Added ability to opt-in/opt-out of Sentry error reporting

### Changed
- Searching now fetches more results as you scroll down

### Fixed
- Fixed issue where selecting the light theme would revert back to dark theme on app relaunch
- Fixed issue where link previews were not being shown properly

## 0.2.0-alpha - 2023-06-20
### Added
- New update in-app notification to notify you of new GitHub releases
- Autofill options for logging into your account (tested on iOS, untested on Android physical device)
- Added an option to switch to a light theme
- Tapping on the community's name within a post will allow you to view the community
- When viewing a community, you can now subscribe/unsubscribe to that community directly
- You can now login with different accounts, and switch between those accounts
- Comments can now be upvoted, downvoted, and saved through swipe gesture
- Tapping on an image will show you a fullscreen view
- Added haptic feedback for some actions
- Vote and comment actions are hidden/disabled when not logged in

### Fixed
- Fixed issue where refreshing or selecting a sort option would cause the feed to show the Local feed

## 0.1.1-alpha - 2023-06-16
### Added
- Switching between tabs keeps the state of the tab
- Added Sentry to allow for debugging and logging

### Changed
- Initial feed now shows a compact version of an image, rather than the full height image

### Fixed
- Fixed issue where if you log in with an instance that does not exist, the community page will indefinitely load
- Fixed issue where a community would show a loading indicator if there were too little posts within that community

## 0.1.0-alpha - 2023-06-15
### Added
- Sorting post feed by hot, active, etc.
- Tap on community name in post to view community
- Upvote, downvote, and save posts
- Seach for communities on the same instance
- Follow and unfollow communities
- Sign in to single account

### Missing Core Features
- No ability to create a post or comment
- No user notifications
- No ability to browse saved comments and posts
- No theming options
- No multi-user ability
- Missing ability to change instances when not logged in