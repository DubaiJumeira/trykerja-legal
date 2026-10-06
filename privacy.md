---
title: Kerja — Privacy Policy
permalink: /privacy/
---

# Kerja — Privacy Policy

## Who we are

Kerja is a professional networking app for digital nomads, starting in Canggu, Bali. This policy explains what personal data the Kerja app and the website trykerja.com collect, why, who receives it, and your rights.

Kerja is run by Zayd Benhacine, an independent developer ("Kerja", "we"). We are responsible for your personal data. Contact us at hello@trykerja.com.

Last updated: 6 October 2026.

## The short version

- **We never store or send your position.** Location is used on the phone only, to centre the map and show distances to cafés. When the map shows your area, Mapbox delivers the map images for it.
- **Your profile is for members.** Signed-in members can see your profile: your name, photo, headline and what you do. People you've blocked, and people who blocked you, can't.
- **Check-ins are café-level.** When you check in, other members see you at that café until you check out, or for 3 hours at most. We delete each check-in 90 days after it ends.
- **Notifications never contain what people write to you.** They're off until you turn them on.
- **No selling, no ads, no tracking** across other apps or websites.
- **Crash reports and statistics are anonymous:** no IP address, no location, no account ID.
- **You can delete your account in the app** (Me → Settings → Delete account). It removes your data from our database and photo storage at once.

## What we collect and why

We collect only what the app needs to sign you in, show your profile to other members, and show who is at which café.

| Data | Where it comes from | Why |
| --- | --- | --- |
| Email address | You (sign-in by code), or Apple or Google | To sign you in and send sign-in codes |
| Name | You; or Google, or Apple at your first sign-in if you share it | To show other members who you are |
| Profile | You: your headline, what you do (for example Developer or Creator), what you're looking for, your city and the date you're there until | To show other members who you are and suggest people to meet |
| Optional profile details | You: your next city and its date, a portfolio link, an Instagram username | To show other members more about your work |
| Profile photo (optional) | You: the one photo you choose | To show other members who you are |
| Privacy choices and blocks | You | To apply them |
| Notification token (optional) | Your phone, if you turn notifications on | To send you notifications |
| Google profile picture link | Google, with your sign-in | Received from Google; not shown in the app |
| Check-ins | You: the café, when you checked in and out | To show who is at a café now |
| Sign-in sessions | Your phone: IP address and device type, per signed-in device | To keep you signed in and protect your account |
| Crash reports | The app, when it fails | To fix bugs |
| Usage statistics | The app: one event when you sign in | To count sign-ins by method |

**Location.** Kerja asks for your location only when you tap the locate button on the map, and only while the app is open. Your position stays in the phone's memory: it centres the map, places your dot and gives distances to cafés. Kerja never stores it and never sends it to us or anyone else. A check-in sends only the café you chose. When the map shows the area around you, Mapbox delivers the map images for that area; it sees the area, not your position.

**Your photo.** Kerja opens your phone's own photo picker, so it sees only the photo you choose, never the rest of your library. Before uploading, the phone crops it square, makes it smaller and saves it as a new image, which removes its hidden details, such as where and when it was taken and which camera took it. Photos are stored privately: the app shows them through links that expire after an hour, and never to people on either side of a block (a link opened just before a block stops working within the hour). Like any app, Kerja keeps a temporary copy of the photos it shows in the phone's cache. Kerja doesn't use your camera or microphone.

**Notifications.** Kerja never asks at launch, and works without them. If you turn them on in Kerja, your phone gives Kerja a notification token, a code that lets us reach that phone; we keep it until you sign out or delete your account. Notifications go through Expo, which passes them to Apple or Google, and they never contain the text of a message or a note someone wrote to you. Only Kerja's server can send them: Expo refuses any request without Kerja's private key. You can turn them off at any time in your phone's settings.

**Sign-in codes.** We keep only a scrambled form of each code, and it expires after one hour. There are no passwords.

**What we don't collect.** No contacts, access to your photo library, camera, microphone, advertising ID or cross-app tracking.

**Legal bases** (EU and UK): providing the service you asked for (account, profile, photo, check-ins); our legitimate interests (security, crash reports, statistics); your consent (location and notification permissions).

## What other members see

- **Your profile, at any time:** signed-in members can see your name, photo, headline, what you do, what you're looking for, your city and the date you're there until, your portfolio link and your Instagram username, and when your profile was created and last updated. Their apps also receive your random member ID and three account flags (LinkedIn verified, work email verified and Pro); none of these is shown, and the flags are always off for now. Kerja doesn't check that an Instagram username belongs to the person who entered it.
- **At a café:** while you're checked in, members see you there: on the map as your photo or initial (up to three people per café, then a number), and in the café's "Who's here" with your name, headline and what you do. With "Show me in who's here" off, you count at the café as a blank circle, never with your name or photo. With "Show which café I'm at" off, you aren't shown or counted at any café. Their apps also receive when you checked in and when your check-in ends. This ends when you check out, or after 3 hours.
- **Your next city and its date:** only members you're connected with, and only while "Share my next city and dates" is on.
- **Blocks:** you and the person you block see nothing of each other. Only you see the people you've blocked, with the date, in Blocked members.
- **Only you see** your email, your check-in history, your privacy choices and your account details.
- **Get directions** opens Google Maps with the café's location, and **Open in Instagram** opens Instagram; their own policies apply there.

## Service providers

These companies process data for us, each only for the job below. We don't sell personal data.

| Provider | Job | What it receives |
| --- | --- | --- |
| Supabase | Database, photo storage and sign-in | Your account, profile, photo, check-ins and notification tokens; your IP address with each request |
| Resend | Sends sign-in code emails | Your email address and the code |
| Apple | Sign in with Apple; notifications to iPhones; TestFlight during the beta | Your sign-in; your phone's notification token and each notification's title and text; testers' feedback; your IP address |
| Google | Sign in with Google; notifications to Android phones (Firebase Cloud Messaging); reCAPTCHA on the website's contact form | Your sign-in; on Android phones, a Firebase installation ID, your phone's notification token and each notification's title and text; your IP address |
| Sentry | Crash reports | What failed, device model, system version, app version; IP address removed, no location, no account ID |
| PostHog | Usage statistics | One sign-in event with a random ID, device model, system version, app version, language, timezone; IP address discarded |
| Mapbox | Map images | Your IP address and the map area on screen; an anonymous usage count. Mapbox telemetry is off |
| Expo | App updates and sending notifications | A random install ID, platform, app version, your IP address; if you turn notifications on, your notification token and each notification's title and text |
| GoDaddy | Hosts trykerja.com | Website visits, contact-form messages and email-list sign-ups (see Website) |
| ImprovMX | Forwards mail to hello@trykerja.com | The emails you send us |

**Mapbox's own setting.** The map's (i) button includes Mapbox's telemetry choice. Kerja turns telemetry off; if you turn it on there, Mapbox collects data under its own privacy policy, and Kerja turns it off again the next time the app starts. Kerja never asks you to turn it on.

When you sign in with Apple or Google, their own privacy policies apply to that sign-in.

## Where your data is stored

Our database and your photo are in Singapore; crash reports and statistics stay in the EU. Sign-in code emails go through Resend's servers in Japan. Other providers above may process data in other countries, including the United States.

When data leaves the EU or the UK, we rely on our providers' safeguards, such as the European Commission's Standard Contractual Clauses. For users in Indonesia, we handle personal data in line with Law No. 27 of 2022 on Personal Data Protection.

## How long we keep it

Your account, profile and settings stay until you delete your account; check-ins go after 90 days; logs, codes, crash reports and statistics expire on their own, as below.

| Data | Kept for |
| --- | --- |
| Account, name, email, profile and photo | Until you delete your account. A photo you change or remove is deleted from our storage at once |
| Privacy choices and blocks | Until you change them or delete your account |
| Check-in history | 90 days after each check-in ends |
| Notification tokens | Until you sign out or delete your account |
| Sign-in sessions | Until you sign out or delete your account |
| Sign-in codes | 1 hour |
| Supabase service logs (with IP addresses) | Up to 7 days |
| Crash reports | Up to 90 days |
| Usage statistics | 1 year |
| Emails to hello@trykerja.com | As long as needed to answer you |

## Your choices and rights

You can change your profile, photo and privacy choices, or delete your account and everything with it, from inside the app.

- **Your profile and photo:** Me → Edit profile, or tap your photo. You can change or remove your photo at any time.
- **Privacy:** Me → Settings → Privacy, to hide which café you're at, leave "Who's here", stop sharing your next city, and see the people you've blocked.
- **Notifications:** Me → Settings → Notifications, or your phone's settings.
- **Delete your account:** Me → Settings → Delete account. Your account, profile, photo, privacy choices, blocks, check-ins, notification tokens and sign-in sessions are removed from our database and photo storage at once. Service logs expire within 7 days; crash reports and statistics aren't linked to your account and expire as above.
- **Sign out:** Me → Settings → Sign out. This signs you out on all your devices and removes their notification tokens.
- **Apple or Google sign-in:** you can also remove Kerja's access in your Apple ID or Google account settings.
- **Location:** allow or refuse it in your phone's settings at any time. The app works without it.
- **Access, correction, a copy, objection or restriction:** email hello@trykerja.com. We answer within one month.
- **Complaints:** you can complain to a data protection authority, for example the one in the country where you live.

## Age, security, website and changes

**Age.** Kerja is for people 18 and over. If you're under 18, please don't use it.

**Security.** Your sign-in on the phone is encrypted, with its key in the phone's secure storage. Data travels encrypted, and database rules let each person read only what they're allowed to see.

**Website.** trykerja.com is hosted by GoDaddy. Its contact form collects your name, email address and message, which GoDaddy stores and forwards to us; if you tick its box, you also join our email list for updates and promotions, and you can unsubscribe at any time. Google's reCAPTCHA protects the form. We keep form messages as long as needed to answer you, and list sign-ups until you unsubscribe. The cookie banner lets you accept or decline cookies that measure traffic; GoDaddy's own privacy policy covers them. This policy itself is published at legal.trykerja.com, hosted by GitHub Pages, which receives visitors' IP addresses.

**Changes.** We update this page whenever the app starts collecting something new, for example when messages arrive. The date at the top shows the last change, and from version 1.0.2 the app tells you when it changes.

**Contact.** hello@trykerja.com