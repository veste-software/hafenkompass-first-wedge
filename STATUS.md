# Hafenkompass (first wedge)

**Stage:** killed · **Platform:** web · **Score:** 5/5 · **Spend:** $0.88

Astro static site: one page per harbour seeded from OpenStreetMap marina data (ODbL) plus facts extracted from public fee schedules and harbour rules (price per m2, waiting-list rules, whether subletting is allowed, contact), each fact with source link and date; a 'berth wanted' form (boat size, region, season) that feeds a public demand count per harbour and sends alerts; a claim flow for operators to post free places and waiting-list status; a swap board shown only where harbour rules allow swaps. Segment: Permanent and seasonal berths on Lake Constance, the Bavarian lakes and the German Baltic coast (Schleswig-Holstein, Mecklenburg-Vorpommern), for boats of 6-14 m.. This is the first wedge of a larger bet, "Hafenkompass": A map of every harbour and marina with berth prices, waiting-list rules and free places, where boat owners post one berth search that reaches many harbours and berth holders offer swaps and unused seasons, starting in Germany and on Lake C… Build only the wedge, and keep the data model and the pages ready for the loop that makes it grow: Every berth search adds to a public demand count per harbour that pulls operators with free capacity to list and update, every listing and swap offer brings more searchers, and more holders on the board make two- and three-way swaps possible.

**Why now:** standing need. Window: Scarcity is rising and visible (Bregenz list grew from about 440 in 2019 to about 1,500; YACHT April 2026 survey), harbours now charge just to stay on lists, and cheap LLM extraction makes it feasible to turn public fee schedules and harbour rules into structured, sourced data.

## Needs you

Nothing right now.

## Recommendation

None yet. The Growth role gives one after launch.

## Metrics

No real numbers yet. Fill in `metrics.json` (Search Console, analytics, Stripe); agents never invent them.

## Target queries

- dauerliegeplatz ostsee
- liegeplatz mieten
- liegeplatz mieten bodensee
- dauerliegeplatz boot
- bootsliegeplatz kosten
- bootsliegeplatz ostsee preise
- liegeplatz chiemsee
- liegeplatz starnberger see
- dauerliegeplatz mecklenburger seenplatte
- liegeplatz kroatien privat

## Alternatives found

- boat24 (berths section) (partial): Static classified ads: the listing I opened says 'price on request' and that the marina is fully booked for 2022 with a waiting list; no live availability, no cross-harbour waiting lists, no swaps.
- Municipal and club harbour waiting lists (e.g. Konstanz berth rules) (partial): Each harbour keeps its own list, typically ordered by application date; applicants must sign up harbour by harbour, pay to stay listed (Bregenz 30 EUR a year) and wait 10-25 years with no view across harbours.

## History

- 2026-11-12 13:36 · scouted · found by manual
- 2026-11-12 13:36 · scouted · ranked first in the daily pool (aggregate 2.2 of 5 by 3 independent rankers, including a Big-bet bonus of 0.3); the studio builds the day's best candidate whatever its score, and the prototype is how it is judged
- 2026-11-12 13:39 · killed · rejected by the product lead: The berth shortage is real, but no payer is shown: BerthFinder already lists German marinas and sends free berth requests and alerts, free for boaters and free to list for marinas (5% of stays), and the few marinas with free berths could only be won by outreach the studio cannot do.
