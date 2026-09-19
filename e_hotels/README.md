# Cluster E · Hotels

Source pack for the team that owns this cluster · links checked 13.09.2026 · DITEC HS26

## The built-in tension
Relay (formerly Savioke) adds one or two delivery robots to a normally staffed hotel. They carry towels and snacks to rooms, ride the elevators on their own and are rented by subscription. Henn-na was built on the opposite logic: robots at reception, in the rooms and at the luggage desk were meant to replace staff. By 2019 it had removed about half of its 243 robots because they created work. This is the cleanest augmentation-versus-replacement pair in the course. Your dossier must show which design and business choices led to each outcome, and what "success" means for each.

Staff-side evidence on Henn-na is already in [staff_acceptance_of_robots.md](../staff_acceptance_of_robots.md) – link to it, do not repeat it.

Note: web.archive.org could not be queried from the checking environment. Where a link failed, an open equivalent is given.

## Deployments
| Deployment | Where | Robot | Since | Status (source, date) |
|---|---|---|---|---|
| Savioke / Relay Robotics hotel fleet | US hotels (Hilton, Marriott, IHG, Hyatt and others) | Relay, Relay+, Relay2 | first hotel test 2014 | Company active; 1,000,000+ deliveries; now also expanding in hospitals (PR Newswire, 03.06.2026). Number of hotel units today not verified |
| Seaview Investors | 8 California hotels (LAX area, Beverly Hills, Healdsburg) | Relay / Relay+ (one per hotel) | 04.2022 | Announced (Robotics 24/7, 20.04.2022); current status unknown |
| Renaissance Las Vegas | Las Vegas | Relay ("Elvis", "Priscilla") | not verified | In use (Hotel Dive, 31.07.2023); later unknown |
| Henn-na Hotel, Huis Ten Bosch (now "Laguna Ten Bosch") | Sasebo, Nagasaki | up to 243 robots | 17.07.2015 | About half the robots removed 2018–2019 (Gizmodo, 15.01.2019). The property is still listed on the official booking site (checked 13.09.2026) |
| Henn-na chain (HIS Hotel Holdings) | Japan, plus Seoul and New York | reception and in-room robots | 2016 onwards | Official site lists 25 properties (checked 13.09.2026). Horwath HTL says "approximately 20"; LavX (08.2025) says "about 150 robots across 14 hotels". The counts conflict; robots per property not verified |

## Core sources
### H1 · Relay Robotics introduces Relay2
- **Link:** https://www.hospitalitynet.org/news/4116700.html – OK
- **Type:** vendor claim (press release) · **Language:** EN · **Date:** 05.06.2023
- **What it gives you:**
  - 10 gallons (41 l) payload, double the earlier model; average delivery 4 minutes from front desk or kitchen to room.
  - Proprietary elevator integration with OTIS, Schindler, TK, Mitsubishi, KONE and others.
  - 1,000,000+ deliveries worldwide; sold as a monthly subscription or RaaS.
  - Context: "87%" of surveyed hotels short-staffed; 402,000+ unfilled leisure and hospitality jobs.
- **Watch out:** all performance figures are the vendor's; no price stated.

### H2 · Henn-na Hotel "fires" half its robot workforce
- **Link:** https://www.hotelmanagement.net/tech/japan-s-henn-na-hotel-fires-half-its-robot-workforce – not verified (HTTP 403 to automated checks, both tools; probably opens in a normal browser) → open equivalents: https://gizmodo.com/robots-ruin-robot-hotel-1831772555 and https://incidentdatabase.ai/cite/346/
- **Type:** press (trade), based on the Wall Street Journal, 01.2019 · **Language:** EN · **Date:** 2019
- **What it gives you (from Gizmodo and the AI Incident Database, which quotes Hotel Management):**
  - About 80 robots in 2015, grew to 243; more than half removed.
  - In-room assistant Churi woke guests during the night; luggage robots reached only a small share of rooms and failed when wet.
  - Check-in dinosaurs needed human help copying passports.
  - Founder Hideo Sawada (WSJ): "When you actually use robots you realize there are places where they aren't needed – or just annoy people."
  - Hotel Management wording (via AIID): the robots "failed to reduce costs or workload for its employees".
- **Watch out:** almost every outlet recycles one WSJ article; there is no primary data from HIS.

### H3 · Henn-na as a replacement-logic failure
- **Link:** https://workshop.horwathhtl.com/resources/case-studies/henn-na-replacement-failure – OK
- **Type:** consultancy case study (secondary) · **Language:** EN · **Date:** not stated
- **What it gives you:**
  - Timeline: opened 17.07.2015; about 80 robots (2015) → 243 at peak (2018); over 50 % removed 2018 to early 2019.
  - Luggage robots could navigate only "~25%" of rooms (Verge-style reports say 24 of 100+ rooms).
  - "Approximately 20" Henn-na properties still operating in 2026.
  - Cites SCMP (16.01.2019), Hotel Management, AIID 346 and the Guardian (2015).
- **Watch out:** no author or date; the 2026 property count conflicts with the official site (25).

### H4 · Savioke Relay at Seaview Investors; early Relay economics
- **Link:** https://robotics247.com/article/savioke_relay_service_robots_work_seven_seaview_investors_hotels – OK (redirects to www.; the fetch tool got 403, a browser check returned 200 and the text was read)
- **Type:** press, based on a vendor press release · **Language:** EN · **Date:** 20.04.2022
- **What it gives you:**
  - A Relay or Relay+ in each of the eight Seaview hotels; Savioke calls this a "U.S. industry first".
  - Savioke: robots installed "in hundreds of hotels", more than 1 million deliveries.
  - Hotels report more bookings from nearby ZIP codes and "hundreds of positive videos and social media reviews".
- **Watch out:** the headline says seven hotels, the text says eight.
- **Link:** https://svrobo.org/?p=3300 – dead (404) → open equivalent for early economics: https://www.cnbc.com/2017/08/24/fedex-and-hotels-and-hire-autonomous-delivery-robots.html
- **Type:** press · **Language:** EN · **Date:** 25.08.2017
- **What it gives you:** Relay leased for "about $2,000 a month on average"; 150,000+ deliveries to date (Savioke); customers included Residence Inn, Crowne Plaza, Westin, Aloft.
- **Watch out:** the "payback in 2–3 months" claim (course §3.3) could not be found in an open source – not verified.

## Go deeper – additional sources
- **Hotel Dive, "Hotel Tech-in"** (31.07.2023) – https://www.hoteldive.com/news/hotel-tech-in-robot-deliveries/689438/
  - Subscription "usually works out to $75,000 over three years, with all maintenance and support costs included" (CEO Michael O'Donnell).
  - "Most hotels that use them have one or two"; strongest value on understaffed overnight shifts.
- **BayCare / Relay hospital expansion** (PR Newswire, 03.06.2026) – https://www.prnewswire.com/news-releases/baycare-expands-autonomous-hospital-delivery-with-new-relay-robots-at-winter-haven-hospitals-302788892.html
  - Vendor and customer claims: 2025 pilot at 99.8 % delivery success with 50 deliveries/day; 500+ deliveries/month projected.
  - New CEO Sultan Mehrabi. Is the company's growth now in healthcare rather than hotels?
- **Relay acquires Savioke** (Robotics 24/7, 2022) – https://www.robotics247.com/article/relay_robotics_acquires_savioke_raises_10m_for_service_robot_expansion – headline seen in search results; content not fetched.
- **Söderberg Granström, Pronk & Criscione-Naylor (2023)**, *Robotic Services in the Hotel Industry: An Examination of Henn Na Hotels*, IJGHT 3(1), open access – https://ijght.org/index.php/light/article/view/63
  - Document analysis, not new guest data.
  - Human-like robots, fear of job replacement and service quality weigh on guest perceptions; standardised tasks add perceived value.
- **Henn-na today** – official booking site (company) https://global.hennnahotel.com/en/ (25 properties incl. Seoul, New York; operator HIS Hotel Holdings). Aggregator https://news.lavx.hu/article/inside-japan-s-henn-na-hotel-the-rise-fall-and-evolution-of-robotic-hospitality (06.08.2025, "adapted from WIRED"): about 150 robots in 14 hotels; staff "from 40 to just eight" at some locations. The WIRED original was not found – treat as not verified.

## Starter questions for your dossier
1. **Context:** hotel size, floors, elevators, night-shift staffing – a limited-service LAX hotel vs a theme-park robot hotel.
2. **Robot:** Relay2 payload, speed, elevator interface, lockable bin vs Henn-na's many specialised robots.
3. **Business model:** US$2,000/month (2017) and US$75,000 over three years (2023), both vendor statements, vs Henn-na's purchased fleet; who pays elevator integration?
4. **Operational evidence:** 1M deliveries, 4 minutes and 99.8 % are all vendor figures; find one independent number.
5. **Staff and customer response:** delivery relief on the night shift vs robots that created work ([staff acceptance briefing](../staff_acceptance_of_robots.md)); guest reviews mentioning the robot.
6. **Failure modes:** voice assistant false wake-ups, rain, room access, passport copying; replacement logic as an organisational failure.
7. **Transfer to the HSLU cafeteria:** requirements for door/elevator hand-off, lockable payload, delivery-time target and "staff notified on arrival".
