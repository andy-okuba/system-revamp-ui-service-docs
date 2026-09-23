---
seo:
  title: Sportsbook Platform API Documentation
  description: Multi-tenant API reference for the sportsbook platform backend services.
---

::u-page-hero{class="dark:bg-gradient-to-b from-neutral-900 to-neutral-950"}
---
orientation: horizontal
---
#top
:hero-background

#title
Sportsbook Platform [API Reference]{.text-primary}.

#description
Multi-tenant backend API contracts consumed by the sportsbook frontend — endpoints, path/query parameters, headers, and precise request/response payloads for backend implementation.

#links
  :::u-button
  ---
  to: /api-reference/fixture-sports
  size: xl
  trailing-icon: i-lucide-arrow-right
  ---
  Browse the API reference
  :::
::

::u-page-section
#title
Table of Contents

#description
Every category of endpoint used by the sportsbook platform, grouped by service. Each category documents the multi-tenant path contract, parameters, headers and sample payloads.

#default
  :::card-group
    :::card
    ---
    icon: i-lucide-goal
    title: Fixture / Sports
    to: /api-reference/fixture-sports
    ---
    Highlights, match details, markets config, live counter, odds status, sports, market aliases, tournaments, categories and search.
    :::

    :::card
    ---
    icon: i-lucide-dices
    title: Betting
    to: /api-reference/betting
    ---
    Bet placement, bet history, WinBoost, boosted bets, booking codes, freebets, cashout and the leaderboard.
    :::

    :::card
    ---
    icon: i-lucide-spade
    title: Casino
    to: /api-reference/casino
    ---
    Categories, games, providers, popular games, game launch, tournaments, results, position and top wins.
    :::

    :::card
    ---
    icon: i-lucide-wallet
    title: Wallet
    to: /api-reference/wallet
    ---
    Balance, bonus balance, transactions, deposits, withdrawals, payment channels and bonus code redemption.
    :::

    :::card
    ---
    icon: i-lucide-user-check
    title: Identity
    to: /api-reference/identity
    ---
    Login, registration, OTP, password reset, device registration, self-exclusion and account management.
    :::

    :::card
    ---
    icon: i-lucide-newspaper
    title: CMS
    to: /api-reference/cms
    ---
    Page metadata, promotions, banners, legal/static content, FAQs, social handles, contacts and popups.
    :::

    :::card
    ---
    icon: i-lucide-trophy
    title: Jackpot / Correct Score
    to: /api-reference/jackpot-correct-score
    ---
    Categories, jackpots, results, bet placement/update, bet history and pre-bet eligibility, across two parallel services.
    :::

    :::card
    ---
    icon: i-lucide-server-cog
    title: Internal Nuxt API
    ---
    Server routes internal to the frontend, e.g. country detection. *(coming soon)*
    :::

    :::card
    ---
    icon: i-lucide-archive
    title: Unused / Configured Only
    ---
    Endpoints configured in runtime environment variables but not directly called by frontend source. *(coming soon)*
    :::

    :::card
    ---
    icon: i-lucide-share-2
    title: Third-Party Endpoints
    ---
    IP detection, BetGames, bet builder, notifications and sports widgets. *(coming soon)*
    :::

    :::card
    ---
    icon: i-lucide-radio-tower
    title: Real-Time MQTT
    ---
    Real-time odds/event updates over MQTT. *(coming soon)*
    :::
  :::
::
