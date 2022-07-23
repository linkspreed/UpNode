# Update 4.2.0 - 17 June, 2021
 - Implemented email reminders for accounts that are on one-time payments (not recurring) 3 days before expiration.

# Update 4.1.0 - 11 June, 2021
 - Implemented the first version of the Plugins Management system.
 - Implemented the first "Offload" plugin, available to purchase here.
 - Fixed a few small bugs.

# Update 4.0.0 - 4 June, 2021
 - Implemented more detailed failed checks on websites monitors.
 - Reworked the checkout flow (better UX) for when the user is required to fill in his billing details.
 - Improved all the emails that are being sent (activation, password reset..etc) for consistency.
 - Updated the bootstrap library to the latest stable release of 4.6.

# Update 3.0.0 - 18 May, 2021
 - Implemented monitor checks separated page with pagination, filters, pdf export, downloadable via JSON, CSV.
 - Implemented monitor SSL Checks.
 - Implemented monitor SSL Certificate expiration notifications via email.
 - Implemented Monitors weekly/monthly reports via email.
 - Implemented Heartbeats weekly/monthly reports via email.
 - Implemented double checks on failed responses for monitors, to minimize false positives.
 - Implemented API status pages statistics endpoint (Read).
 - Fixed ping server couldn't be deleted.

# Update 2.1.0 - 15 April, 2021
 - Improved UX for the Reset Password, Resend Activation, Lost Password pages.
 - Fully reworked all the statistics related charts: now they are grouped results by years, months, days & hours based on the selected date range.
 - Fixed page categories not being able to be selected when creating/updating a page.
 - Fixed taxes not being able to be selected when creating/updating a plan.
 - Fixed twilio notifications not being linked to a proper translation.

# Update 2.0.0 - 2 April, 2021
 - Implemented Webhook URL notifications for Monitors and Heartbeats.
 - Implemented Slack notifications for Monitors and Heartbeats.
 - Implemented SMS notifications for Monitors and Heartbeats.
 - Implemented Custom Domains API - Create, get list, get one, update, delete.
 - Implemented Payments API - Get list, get one.
 - Implemented Logs API - Get list.
 - Implemented Monitors API - Get list, get one.
 - Implemented Heartbeats API - Get list, get one.
 - Implemented Status Pages API - Get list, get one.
 - Implemented Projects API - Create, get list, get one, update, delete.
 - Implemented the ability to set a custom not found page for custom domains.
 - Implemented language detection based on the browser in certain cases, where possible.
 - Implemented the ability to delete already set status page favicons and logos.
 - Fixed multiple bugs related to custom domains.
 - Fixed user activation with the activation email bug.
 - Multiple other behind the scenes improvements on the code & bugfixes.

# Initial release - 26 March, 2021
