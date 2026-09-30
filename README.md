# Seif Younes

I build websites and mobile apps with Next.js, Flutter and Supabase, using AI coding agents (Claude Code, Codex). The
agents write the code. I plan each feature, review the changes the agents make and test them on real devices.
Mechatronics Engineering student at Alexandria University (graduating 2028) with a flexible schedule, based in
Alexandria, Egypt and available for full-time remote work.

Email: seifyounes222@gmail.com · [LinkedIn](https://www.linkedin.com/in/seif-younes12/)

## PureChem, an agrochemicals company website (live)

Live at [purechem-website.vercel.app](https://purechem-website.vercel.app/). Shown with the client's permission; some
details in the screenshots are blurred.

A bilingual Arabic/English (RTL/LTR) Next.js 15 product catalogue with 76 prerendered pages and quote and contact
forms. I did the design, the build (directing AI coding agents), and the content and media.

- First version handed over in 3 days. PureChem rehired me for new pages.
- The client says the site brings in 100+ quote requests a month.

<p>
  <img src="images/client-home-desktop.png" width="600" alt="PureChem home page in English (some details blurred)">
  <img src="images/client-home-mobile-ar.png" width="195" alt="The same home page in Arabic on mobile (some details blurred)">
</p>
<img src="images/client-products-desktop.png" width="600" alt="Product catalogue with category filters and search">

## Elite, a habit app for iOS and Android (in private testing)

Flutter, Riverpod, Supabase. In private testing with 3 friends; not in the app stores. The source is private; these are
screens from a test build with test data.

<p>
  <img src="images/elite-home.png" width="200" alt="Elite home screen: streak, level and the workload bar">
  <img src="images/elite-habits.png" width="200" alt="Elite habits list with each habit's workload weight">
  <img src="images/elite-identity.png" width="200" alt="Elite onboarding: the user writes an 'I am the person who…' statement">
  <img src="images/elite-insights.png" width="200" alt="Elite insights: completion rate by weekday and records">
</p>

- Check-ins made offline are queued and sent exactly once when the phone reconnects.
- Home-screen widgets on iOS and Android tick off a habit without opening the app.
- The agents write the tests; I decide what each one checks and review them. The 3,400+ unit and widget tests confirm
  the score and streak math matches the database and no personal data reaches the logs.

## Lofty, an idea tracker (live)

Ideas float as physics-driven balloons (matter-js), sized by scope and ranked by priority. Next.js 14 and TypeScript;
ideas are saved in the browser.

- Demo with sample ideas: https://lofty-two.vercel.app/demo
- Source: [seifyounes/lofty](https://github.com/seifyounes/lofty)

## AI news agent

A Claude Code agent that scores AI news on 5 criteria and keeps only stories rated 8/10 or higher. It has written 60+
digests since July 2026.

- Source: [seifyounes/ai-news-agent](https://github.com/seifyounes/ai-news-agent)
