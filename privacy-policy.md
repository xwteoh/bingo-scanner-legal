# Bingo Scanner Privacy Policy

**Last updated:** November 11, 2026

Bingo Scanner ("the App") is operated by Xin Wei Teoh ("we", "us"). This policy explains what information the App uses, who receives it, and the choices you have.

**In short:** the App has no accounts, and your cards and games stay on your phone. Information reaches other companies only as listed in section 3. The main examples are data Google collects for ads, crash reports sent to Sentry and, from version 1.1.1, anonymous usage statistics sent to PostHog if you agree. In version 1.1 and later, card photos stay on your phone.

## 1. Card Photos

- **Version 1.1 and later:** the App reads your card using Google ML Kit on your device. Your card photos aren't sent over the internet.
- **Versions before 1.1:** the App first tries Google ML Kit on your device. If that fails or isn't available, it sends the card photo over the internet to the Google Cloud Vision service to read the numbers, without asking you first. Google states that images in these requests are processed in memory, aren't saved to disk and aren't used to train its models, and that it temporarily logs some request metadata. Update the App to stop this.
- **Not sent to us:** we don't run servers for the App and don't receive your photos.
- **On your phone:** a scanned photo may stay in the App's storage on your device until the App is removed. Apart from the Google Cloud Vision step in versions before 1.1, it isn't shared unless you choose to share something yourself.

## 2. Information Stored on Your Phone

The App keeps these on your device. We can't see them:

- Your cards, called numbers, saved game and saved card library
- Your settings and preferences, including ad consent status and whether usage statistics are on
- Your Bingo Plus status and purchase reference
- Usage counters, such as the number of game sessions and when an ad was last shown
- Usage statistics waiting to be sent, and the random identifiers they use
- A short log of app errors

Win notifications are created on your phone and aren't sent through a server. Removing the App deletes most of this. On iPhone, your Bingo Plus status may stay in the phone's secure storage after removal. Your phone's own backups may include App data.

## 3. Services That Receive Information

| Service                               | What it's for                                                          | What it may receive                                                                                                                                                                                                                                                                                               |
| ------------------------------------- | ---------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Google AdMob and consent tools**    | Ads for free users, ad consent                                         | IP address, which can suggest your general location; advertising and device identifiers; ad and app interactions; diagnostics; consent choices                                                                                                                                                                    |
| **Google ML Kit**                     | On-device card scanning                                                | Device and app details, an installation identifier, performance data and error codes, for diagnostics and usage analytics                                                                                                                                                                                         |
| **Google Cloud Vision**               | Backup card scanning in versions before 1.1 only                       | Your card photo, as described in section 1. These versions also make simple internet connection checks to Google                                                                                                                                                                                                  |
| **Sentry**                            | Crash and error reports in version 1.1 and later                       | Error details and code locations, the screens and buttons used just before the error, device and system details such as model, system version, language and time zone, app version, and an installation identifier. Sending a report also passes your IP address to Sentry, which we've set not to store it       |
| **Apple and Google in-app purchases** | Buying and restoring Bingo Plus                                        | Your purchase. Apple and Google handle payment, and we don't receive your card details. They give us sales reports                                                                                                                                                                                                |
| **PostHog**                           | Anonymous usage statistics in version 1.1.1 and later                  | The steps you reach in the App, scan results, free or Plus status, your phone's region setting, device and app details, a random installation identifier and a random session identifier, as described below. Sending also passes your IP address, which we've set PostHog not to store                           |
| **Expo**                              | App update services                                                    | When the App checks for updates: platform, app and update versions, an installation identifier and IP address                                                                                                                                                                                                     |
| **Tally**                             | Support form, and an optional player survey in version 1.1.1 and later | Opening the support form sends your app version, device system, free or Plus status, game session count and IP address. Opening the survey sends your app version, device system, free or Plus status and IP address. Submitting either adds what you type. Tally says it doesn't store IP addresses with answers |
| **Google (Gmail)**                    | Support email                                                          | If you email us: your email address and message                                                                                                                                                                                                                                                                   |

In versions before 1.1, ad components may also start for Bingo Plus owners when the App opens, though they aren't shown ads.

Crash reports aren't designed to include your card photos, saved cards or screenshots, and the App removes email addresses and purchase tokens from JavaScript error reports before sending them. Versions before 1.1 don't use a crash-reporting service.

Usage statistics record steps such as opening the App, adding a card, starting a game, calling its first number, winning, starting another round, seeing the Bingo Plus offer, buying or restoring Bingo Plus, sharing a win and seeing a full-screen ad. They also record how well scans went and how many cells you corrected, and your choice on the survey card. Device and app details means the App's name, version and build, device maker and model, system name and version, screen size, language and time zone, and whether the App is running on a simulator. The session identifier groups the statistics from one use of the App, and changes when you reopen the App or after 30 minutes without use. PostHog doesn't use your IP address to work out your location. Usage statistics never include your card numbers, card names, photos, or payment or transaction details, and they aren't linked to your name or email address. Versions before 1.1.1 don't send usage statistics.

We don't sell your personal information. Each service handles data under its own privacy policy:

- [Google](https://policies.google.com/privacy)
- [Apple](https://www.apple.com/legal/privacy/)
- [Expo](https://expo.dev/privacy)
- [PostHog](https://posthog.com/privacy)
- [Sentry](https://sentry.io/privacy/)
- [Tally](https://tally.so/help/privacy-policy)

## 4. How Information Is Used

We use this information to scan cards, run your game, provide and restore Bingo Plus, show ads to free users, answer your support requests, fix problems, and learn from usage statistics and survey answers what to improve.

## 5. How Long Information Is Kept

- **On your phone:** until you delete it or remove the App. Saved games are cleared when you start a new game or when you open the App and the save is over 24 hours old. Your phone may keep scan photos until the App is removed.
- **Support messages:** only as long as needed to help you, unless a law requires longer. You can ask us to delete them.
- **Survey answers:** as long as they help us improve the App. If you gave contact details, you can ask us to delete them.
- **Crash reports:** Sentry keeps them for a limited time, then deletes them.
- **Usage statistics:** PostHog deletes them about a year after they're sent.
- **Other services:** according to their own policies.

## 6. Your Choices

- **Ad consent:** where it applies, choose or change your ad preferences in **Settings → Manage Ad Consent**.
- **Ad tracking:** use your phone's settings. On iPhone, you can refuse tracking when asked. On Android, you can reset or delete your advertising ID.
- **Camera:** you can turn off camera access in your phone's settings, and enter cards by hand instead.
- **Player survey:** answering is optional. The invitation stays on the home screen until you open it or tap **No Thanks**. Bingo Plus owners see it straight away, and free players after a few games. If you later buy Bingo Plus, the App invites you once more. Your answers aren't linked to your name unless you give contact details in the survey or, from the same browser, in our support form.
- **Usage statistics:** the App asks once whether to send them, and they stay off unless you say yes. Change your answer any time in **Settings → Privacy → Help Improve Bingo Scanner**. Turning them off stops new statistics at once, though anything recorded in the few seconds before may still be sent. It also deletes the random installation identifier from your phone. Statistics already sent stay with PostHog until it deletes them. They aren't linked to your name or email address, so we usually can't find the statistics from a particular phone.
- **Crash reports:** in version 1.1 and later, these are sent automatically and the App has no setting to turn them off. They aren't linked to your name or email address, so we usually can't find the report from a particular person.
- **Your data:** contact us with any question or request about your information. Because the App has no accounts, most of your data is on your phone, where you control it.

## 7. Children

The App isn't intended for children under 13, and we don't knowingly collect their information. If you believe a child has sent us information, contact us and we'll delete it.

## 8. Security

Information sent to these services travels over encrypted connections, and the App uses your phone's secure storage for Bingo Plus status where available. No system is completely secure.

## 9. International Transfers

Google, Apple, Expo, Sentry, PostHog and Tally may process information in other countries, including the United States. Our crash reports are sent to Sentry's European Union region, and usage statistics to PostHog's European Union region.

## 10. Changes to This Policy

If we change this policy, we'll update the date at the top. We'll highlight significant changes in the App where we can.

## 11. Contact Us

- **Email:** [project.bingo.scanner@gmail.com](mailto:project.bingo.scanner@gmail.com)
- **In the App:** Settings → Report a problem
- **Support form:** [https://tally.so/r/q5DZlY](https://tally.so/r/q5DZlY)

## Manage or Revoke Ad Consent {#manage-consent}

To change your ad preferences:

1. Open Bingo Scanner.
2. Go to **Settings → Manage Ad Consent**.
3. Follow the consent dialog to update or withdraw permission.

The option only has an effect where a consent form applies to your region.
