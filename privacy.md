---
layout: default
title: EA Backup privacy policy
---

# EA Backup privacy policy

EA Backup is for the operator's personal use only. It is not offered to other users.

## Data access and purpose

The application uses Google Drive authorization to create backup files and access files authorized for the application. File contents and metadata are processed for backup transfer, comparison, previous-version retention, and restoration. Access is limited by the requested `drive.file` scope.

## Storage and sharing

Backup files are stored in the operator's Google Drive. OAuth client credentials and authorization tokens are stored locally on the operator's computer in a restricted configuration directory. Local operation logs may contain filenames and transfer results.

The backup configuration does not send backup contents or credentials to this website. It does not sell Google user data or use it for advertising or AI model training. Transfers are between the operator's computer and Google Drive; rclone is the local transfer software.

Use of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including its Limited Use requirements.

## Retention and control

Backup files and saved previous versions remain until the operator removes them. Revoking the application's Google account access stops future authorized access; it does not automatically delete existing backup files or local credentials. The operator controls those separately.

## Website hosting

This documentation site contains no application analytics, advertising, or login forms. GitHub Pages, if used to host it, may process access information under [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

The operator maintains this policy when the backup configuration's data practices change. The operator's support contact is provided on the Google OAuth consent screen.
