---
title: Privacy Policy
permalink: /en/privacy/
---

# Privacy Policy

Effective: September 6, 2026
Last revised: October 8, 2026

Elpis ("we", "us") operates the health-habit app Elpis (the "App"). This policy
explains what information we collect and how we handle it.

**The App handles health-related information.** What follows describes what we
actually collect, as the App is built — not a generic template.

日本語版は [こちら]({{ site.baseurl }}/privacy/)。

---

## 1. Information we collect

### 1-1. Account identifier

**You can start using the App without providing a name or an email address.**
On first launch, an anonymous account is created automatically and assigned a
single identifier. At that point, that identifier is the only information we hold
about you.

If you choose to link an Apple or Google account, we receive the following from
that provider:

| Provider | What we receive |
|---|---|
| Apple | An identifier issued by Apple, and an email address |
| Google | An identifier issued by Google, and an email address |

When linking with Apple, you may choose **Hide My Email** on Apple's screen. In
that case we receive Apple's relay address, not your personal address.

Linking is optional. Every feature of the App, including the subscription, works
without it.

### 1-2. Records you enter

| Type | Content |
|---|---|
| Mood | A value from 1 to 5 |
| Habits | Whether each habit you configured was done. Habit names, including ones you type yourself |
| Journal | Free text, up to 2,000 characters |
| Screen time | Minutes per day |

**A day with no record is kept as a day with no record.** We do not fill gaps
with zeros or averages.

### 1-3. Body data (only if you allow it)

Only if you explicitly grant permission on your device, we **read** the following
through Apple Health (HealthKit) on iOS or Health Connect on Android:

- Resting heart rate
- Step count
- Sleep (start and end times)
- Active energy burned

**We never write data back to HealthKit or Health Connect.** You can revoke
permission at any time in your device settings; we stop reading new data from
that point on.

### 1-4. Screen time (Android only, if you allow it)

On Android, if you grant "Usage access", we read your total device usage for the
day and pre-fill it in the record screen.

**We do not collect this on iOS.** Apple's Screen Time API does not permit
third-party apps to read the values.

We do not collect the names of other apps or per-app usage. Only the daily total.

### 1-5. Information generated inside the App

Monster growth, walk records, materials you hold, items you craft and where you
place them, your collection, and notification settings.

### 1-6. Subscription information

If you subscribe to Elpis Plus, we receive the subscription status, a subscriber
identifier, the plan identifier, and the expiry date through our payments
provider (RevenueCat, Inc.).

**We never receive your credit card number or other payment details.** Payment is
processed by Apple (App Store) or Google (Google Play); we only learn whether a
subscription is active.

### 1-7. How the App is used (behavioural data)

To improve the App and investigate faults, we record **what you do inside the App**.

| What | Detail |
|---|---|
| Screens | Which screens you opened |
| Features used | Tapping record, walk, craft, or open the egg, and coming back from a walk |
| The **fact** of a record | That you saved a record, that you closed without saving, how long the entry took, and whether it was for today or an earlier date |
| Growth | That a monster evolved or left the nest, and which cycle it was |
| Subscription funnel | That you viewed the Elpis Plus page, and that you subscribed |
| Notifications | That you opened the App from a notification |
| Getting started | How far through the initial setup you got |
| Faults | The circumstances of a crash, and the error itself |

**The contents of your records are not included.** Your mood scores, habit names,
whether you completed a habit, your diary text, sleep, steps and screen time are
**never sent**. What we send is the fact that a record was saved, and how many
seconds it took.

This data includes the **identifier described in 1-1**. It does not include your
name or email address.

Fault reports can contain technical details, such as the address of a request
that failed. That identifier may appear in them. The contents of your records
do not.

### 1-8. Your name (only if you enter one)

If you enter it during setup or in Settings, we store a name (up to 20 characters)
that your monster uses to address you. It is optional, and a nickname is fine.
It is used in the weekly report summary.

### 1-9. AI-written weekly summary (only if you agree)

The "This week" summary in the weekly report is written by an AI (Claude, by
Anthropic, PBC) **only if you agree**. To do that, we send Anthropic the following:

| What | Detail |
|---|---|
| Day counts | How many days you recorded that week, and on how many you did a habit |
| Body changes | Whether your sleep or steps were better than last week (**only when they were; no numbers are sent**) |
| A habit name | The name of one habit you did most that week (this can be a name you typed yourself) |
| Your name | Only if you entered one (1-8) |

- You agree or decline through the prompt shown in the weekly report, or in
  **Settings > Weekly review > AI summary**. If you do not agree, **nothing is
  sent** and the summary is shown using pre-written text
- You can withdraw at any time in the same setting. Nothing is sent after that
- Your mood scores, diary text, sleep and step numbers, and screen time are
  **never sent**
- The written summary is stored by week in the location described in section 3,
  along with your choice

---

## 2. What we do not collect

To be explicit, we do not collect:

- **Location**
- **Contacts**
- **Camera, microphone, or photos** (except if you take part in an interview — see section 7)
- **A list of other apps on your device**
- **Advertising identifiers (IDFA / AAID)**
- **Payment card details**

The App does use analytics, as described in 1-7. **What it never sends is the
content of your records** — mood, habits, diary, body data and screen time stay
out of it. Only your actions and the state of the App are sent.

The AI-written weekly summary (1-9) is separate from analytics and happens only
if you agree.

**There is no setting that turns analytics off on its own.** If you would rather
not send it, you can delete your account (section 8) or stop using the App.

---

## 3. Where information is stored

| What | Where |
|---|---|
| Records, body data, monster data, subscription status | Supabase (**Tokyo region**) |
| Behavioural and fault data (1-7) | Google's servers (Firebase / Google Analytics). A copy for analysis sits in BigQuery, **Tokyo region** |
| Some display settings, such as room theme | Only on your device |

Your records are stored on servers in Japan. The provider, Supabase, Inc., is a
US company, and its staff may access the infrastructure in the course of
operating and maintaining it (see section 6).

---

## 4. Why we use it

We use the information only to:

1. Provide the App's features — storing and showing your records, growing the
   monster, estimating effects, and generating weekly reports (including an
   AI-written summary, if you agree)
2. Provide and manage the Elpis Plus subscription
3. Respond to your enquiries
4. Investigate faults and improve the App
5. **Conduct research and interviews to improve the App** (see section 7)

**We never use the content of your records for advertising.**

---

## 5. Disclosure to third parties

We do not disclose your information to third parties except with your consent or
where required by law.

**We do not sell your information.**

### Health data from HealthKit and Health Connect

For the body data described in section 1-3, we additionally commit that we:

- **Do not use it for advertising or marketing**
- **Do not sell or transfer it to third parties**, including data brokers
- Do not disclose it to third parties without your explicit consent. Only if you
  agree to 1-9, we send Anthropic whether your sleep or steps were better than
  last week (no numbers) to write the weekly summary
- Do not use it for any purpose other than providing the App's features

---

## 6. Processors and international transfers

We rely on the following providers, all incorporated in the United States.

| Provider | Purpose | Where data sits |
|---|---|---|
| Supabase, Inc. (US) | Database and authentication | Japan (Tokyo region) |
| RevenueCat, Inc. (US) | Subscription management | United States |
| Apple Inc. (US) | Account linking, App Store payments | United States |
| Google LLC (US) | Account linking, Google Play payments, **analytics of behavioural and fault data** (Firebase / Google Analytics) | United States (analysis copy in Japan) |
| Anthropic, PBC (US) | **Writing the weekly summary** (1-9; only if you agree) | United States |

Data protection rules in the United States differ from those in Japan and other
countries. Please also review each provider's own privacy policy.

---

## 7. Research and interviews

We may run **paid interviews, recruited publicly**, to improve the App.

- **Taking part is voluntary.** Declining costs you nothing and has no effect on
  the App's features or your subscription
- Compensation is paid **for taking part in the interview**. Whether you kept
  using the App, or kept up your records, is not a condition of payment
- Interviews are **recorded and transcribed**. We confirm consent to recording
  individually before we start
- We may quote what you said in our own writing — blog posts, social media,
  presentations. **Quotes are anonymised.** We do not include names, employers,
  or where you live
- For participants only, and **only within the scope you have agreed to**, we may
  look at your recorded data for research purposes. We never do this without
  consent
- Recordings, transcripts, and data examined for research are kept for at most
  **two years from the date of the interview**, then deleted
- Within that period you can still ask us, through the contact form in section
  11, to delete the recording and transcript

We do not examine the records of people who have not taken part in an interview
for research purposes.

---

## 8. Retention and deletion

### Deleting your account

You can delete your account at any time from **Settings > Data > Delete account**
in the App. **This works even if your account is still anonymous and unlinked.**

Deleting removes all of the following:

- Your account identifier and anything received from a linked provider
- Your name and your choice about the AI-written summary
- Every record (mood, habits, journal, screen time)
- Body data
- Monsters, collection, materials, crafted items, and their placement
- Weekly reports
- Stored subscription status

**Deletion cannot be undone.** We cannot restore data from backups.

Behavioural data (1-7) is the exception: it stays with the analytics provider.
See "How long behavioural data is kept" below.

### What deletion does not stop

**Deleting your account does not cancel your App Store or Google Play
subscription.** You must cancel it separately in the store's settings (see the
Terms of Service, section 5).

### How long behavioural data is kept

Behavioural data (1-7) is deleted automatically **14 months** after it is
collected. Fault reports are deleted on Google's schedule, roughly 90 days.

**Deleting your account does not remove it.** It carries the identifier from 1-1,
but the analytics provider holds it without any link to the contents of your
records, and it expires on the schedule above.

### If you do not delete your account

We retain your information for as long as the account exists. We do not set a
fixed retention period.

---

## 9. Your rights

You may ask us to disclose, correct, suspend the use of, or delete the
information we hold about you. Please use the contact route in section 11.

Most viewing, correcting, and deleting can be done by you directly in the App,
including deleting the whole account (section 8).

Depending on where you live, you may have additional statutory rights. If you
believe we have not handled a request properly, contact us and we will look at it
again.

---

## 10. Changes to this policy

We may revise this policy as the law or the App changes. When we do, we publish
the revised policy and its "Last revised" date on this page.

---

## 11. Contact

For questions about this policy, or to make a request under section 9:

- Trading name: Elpis
- Contact form: [https://forms.gle/8kfrTeD7yTGLdTM96](https://forms.gle/8kfrTeD7yTGLdTM96)

---

## 12. Children

If you are under 16, please use the App only with the consent of a parent or
guardian. The App is not directed to children under 13.

---

[Terms of Service]({{ site.baseurl }}/en/terms/) · [Support]({{ site.baseurl }}/en/support/) · [Home]({{ site.baseurl }}/) · [日本語]({{ site.baseurl }}/privacy/)
