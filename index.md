# TradeGuard Privacy Policy

Effective: October 9, 2026
Contact: info.tradeoraclefx@gmail.com

TradeGuard ("we", "the app") is a trading journal, risk-management, and paper-trading companion for iOS and Android. This policy explains what we collect, why, and your choices.

## 1. Data we collect
- **Account data:** email address and authentication credentials via Supabase Auth (or Sign in with Apple / Google if you choose those).
- **Broker connections:** MetaAPI account identifiers and labels needed to monitor equity and execute paper or live copy orders. Broker login passwords are never stored by TradeGuard.
- **Journal data:** trades you import or record, notes, checklist grades, and screenshots you upload. Screenshots live in a private storage bucket accessible only to you.
- **Guard data:** equity snapshots and drawdown/guard events used for alerts. Guard event history is retained for 30 days.
- **Copy-trading data:** your copy settings (risk limits, live consent, kill-switch state) and signal-follow records (paper and live).
- **Purchase data:** subscription status via RevenueCat. Payment details are handled entirely by Apple App Store / Google Play; we never see them.
- **Device and usage data:** Firebase Analytics and Crashlytics collect device model, OS and app version, coarse feature-usage events, and crash reports. We deliberately do not log emails, names, or trade contents into analytics.
- **AI processing:** when you request AI trade review or chart analysis, the relevant trade/chart data is sent to the OpenAI API to generate the response.
- **Push tokens:** an FCM device token so guard alerts can reach you.

## 2. How we use data
To operate the features you request (journaling, guard alerts, copy execution, AI review), to secure your account, to handle support requests, and to comply with law. We do not sell personal data and do not use your journal content for advertising.

## 3. Sharing
Only with the processors that operate the service: Supabase (hosting and storage), Firebase (analytics, crash reporting, push), RevenueCat (subscriptions), MetaAPI (broker connectivity), TwelveData (market data), and OpenAI (AI features).
**Affiliate disclosure:** broker offers shown in the app may use affiliate links; we may earn a commission at no extra cost to you.
No other sharing occurs except where compelled by law.

## 4. Retention
Guard events: 30 days. Journal entries, screenshots, follows, and copy settings: until you delete them or your account. Crash and analytics data: retained in aggregated or anonymized form per Firebase defaults.

## 5. Security
All personal tables are protected by row-level security; storage buckets are private and owner-scoped; server-side keys are separated from the client. No method of electronic storage is absolutely secure.

## 6. Your rights and deletion
- **Access / export:** email us and we will provide a copy of your data.
- **Deletion:** use **Settings → Delete Account** in the app (immediate), or email us from your registered address; verified requests complete within 30 days. See our Account Deletion page for details.
- **Subscriptions:** deleting your account does **not** cancel an active subscription. Cancel via App Store or Play Store subscription settings.

## 7. Children
The app is not directed to individuals under 18 and we do not knowingly collect their data.

## 8. Changes
Material changes will be announced in-app or by email before taking effect.

## 9. Financial disclaimer
TradeGuard is a journaling, analytics, and simulation tool. Nothing in the app is investment advice. Trading involves substantial risk of loss.
