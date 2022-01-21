# WordPress Plugin - Auto Login New Users
 WordPress plugin to log in new users through an auto-generated link in their welcome email

## Description
Automatically log in new users by clicking a generated one-time-use link and adds it to the user profile.

- Happens on user creation automatically
- Only stores partial link in db for better security
- Expires after first use

## Installation
1. Upload \"auto-login-new-users\" folder to the \"/wp-content/plugins/\" directory.
2. Activate the plugin through the \"Plugins\" menu in WordPress.

## Frequently Asked Questions
**Q:** Are there any security risks with this ability? =
**A:** Not that we have found. The keys used are salted and timestamped.

## Changelog
> ### __1.0.0__
> - Initial release.
