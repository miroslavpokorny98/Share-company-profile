# Slack Signal Log

_Last synced: 2026-04-08_
_Channels: #internal-share (C0ANQLPG4S1), #vkz-share (C0AM7KVU84C)_
_Rule: **READ-ONLY**. Never send or edit messages in these channels._

---

## How to use this file

- Chronological capture of relevant Slack messages from both channels.
- On re-sync, read both channels with `slack_read_channel`, append only messages newer than "Last synced", and bump the timestamp at the top.
- Topic-worthy signal gets propagated into the appropriate doc (`SHARE_SUMMARY.md`, `research/topics/*`, `research/calls/*`) — this file is the audit trail, not the source of truth.
- Channel tag prefix: `[INT]` = #internal-share (VKZ team), `[CLI]` = #vkz-share (client-facing).
- Many client messages come from accounts where the user name didn't render in the API response — attribution is "Share team" when uncertain.

---

## 2026-04-08

- **[CLI]** Luis: *"hey @Thao @Miroslav good morning! When do you think we'll have a budget & breakdown + timelines?"* (09:31 CEST)
- **[CLI]** Thao: confirmed budget breakdown coming within the hour (09:32)
- **[CLI]** Luis: asked for the Mapbox visualization link Miroslav had shared earlier (09:54)
- **[CLI]** Thao: sent detailed budget breakdown spreadsheet (Google Sheets) with notes:
  1. Most immersive part is the homepage. Real-time rendering — more demanding on dev but stronger impact, faster loading, more flexible than PNG sequence.
  2. Suppliers, ISPs, Users pages will be simpler / less animation-heavy. Reuse selected 3D elements from homepage to maximize investment + visual consistency.
  3. Resources section: one archive page + one template per content type (article, press release, case study). All editable via CMS.
  4. Form builder system included — flexibility to bring forms onto the website later.
  5. Annual fee covers hosting, maintenance, bug fixes, package updates, server management.

## 2026-04-07

- **[INT]** Miroslav: shared mapbox.com/telco
- **[INT]** Miroslav: shared topoexport.com
- **[INT]** Miroslav: shared YouTube visual reference (`youtube.com/watch?v=QBYr0k8dOtw`)
- **[INT]** Thao to Lukáš: forwarded Jose's Apr 6 homepage narrative breakdown for prep before the next-day call. Czech: *"Mrkni prosím na tohle před callem zítra"* (please look at this before the call tomorrow). Full narrative copy attached (Hero / Opportunity / Bridge / Practical Offering / Expansion / Closing Tagline).

## 2026-04-06

- **[CLI]** Share team (16:54 CEST): *"thanks a lot for sharing everything over and for the detailed notes. Apologies for the slight delay on our side, we've had public holidays here so things have been a bit slower. We're going through everything now and will be putting together the promised budget and breakdown shortly."* — note: this looks like Thao acknowledging on VKZ's side, not Share. (Czech Easter holidays Apr 4-6.)
- **[CLI]** Share/Jose (16:54): *"Sounds good Thao! Happy Easter"*
- **[CLI]** Jose (10:37): sent detailed website structure update — **4 pages**, adding Suppliers (which wasn't in the previous breakdown):
  1. Homepage
  2. **Suppliers / Infrastructure** (supply side of marketplace) — NEW
  3. For ISPs (demand side)
  4. Users
- **[CLI]** Jose (10:37, Homepage Narrative Breakdown): canonical hero copy and section structure:
  - **Hero (FOR ALL):** *"Share is a carrier-neutral, open-access internet infrastructure network. Our purpose is to coordinate and enhance the overall productivity of the telco industry across the entire African continent."* Opens with strong visual: interconnecting large amounts of infrastructure, activating it, making sense of it through coordination of light.
  - **Opportunity / Problem (UNDERUTILIZED INFRASTRUCTURE):** *"Africa is poised to become one of the richest telecommunication infrastructure markets in the world. Yet coordination across all key players is completely missing. Despite an abundance of infrastructure, from undersea cables to tower networks, fiber optic lines, and data centers, hundreds of millions of people remain disconnected from reliable, high-speed connectivity, which is the foundation of today's society."* Visual: cables not being connected, becoming useless without coordination.
  - **The Bridge — Share (ONE TRUST LAYER):** Introduce Share as the *"trusted financial and OS coordination layer the internet was missing."* Frame as trust-based financial and operational intelligence layer.
  - **Practical Offering (PRACTICAL USE):** *"Providing the Fastest Internet. Everywhere."* Acceptance everywhere across the Share Network — people connect to infrastructure or to devices. Earlier broken cable becomes unified. Show interoperability everywhere from a device standpoint (one cable comes to a device → multiple cables connect to a single device).
  - **Expansion:** *"Africa's shared backbone, one payment layer."* Visual: one single point of connection expands → boom → one shared backbone, one payment layer.
  - **Closing Tagline:** *"The Internet, from Africa to the World"*
- **[CLI]** Jose (10:37, tone direction): *"we'd like the lighting and color palette, particularly the bright blue tones, to feel more 'tech-forward,' with a subtle war room atmosphere. This could include muted, slightly desaturated colors with a darker overall depth, creating a more focused and controlled environment rather than something bright or overly vibrant. Giving the connections more strength by their light contrast."*
- **[CLI]** Jose (10:37, Supplier Page reasoning): *"to communicate to all the infrastructure owners and players in the industry, from data centers to tower companies to subsea cable providers. It is an opportunity for those that have existing unused or underutilized capacity to be able to get exposed to a market in which they can make money. It's the idea of those that might be seen as competitors to see themselves as opportunistic in the opportunity they have to make more money on their balance sheet through our marketplace."*
- **[CLI]** Jose (16:46, ISP Page content):
  - **Hero:** *"Eliminate every infrastructure and capacity bottleneck. Share gives you access to multiple IPT providers, L2 services, and national backbones, all acting as one unified network. Revenue share only. No per-megabit charges, no commits. Sell the fastest speeds, make better margins."*
  - **Section 2:** *"Connect at any data center, cell tower, or fiber route. A single cross-connect gives you access to Share's full network. No matter where you operate, a Data Center, a tower site, or a joint box along a fiber route, one physical handoff is all it takes. Share runs on new and existing fiber already deployed by tier-one providers. Expanding into a new area means no upfront capex to deploy and no opex to maintain. The fiber is already there. You hit the market running."*
  - **Section 3:** *"Keep your systems. We integrate with them. Share connects directly to your existing OSS/BSS and billing platform. No migration, no rip-and-replace. Your subscribers, your plans, your workflows, everything stays where it is. Through your existing platform, you can now provision, monitor, and manage subscribers across every city Share operates in, as if it were all your own infrastructure."*
- **[CLI]** Jose (10:37): *"We'd love to receive a detailed itemized breakdown / invoice of what the cost would look like for the website as presented by you last week. Please include the cost per page and any other line items so we can review on our end."*

## 2026-04-02

- **[CLI]** Concept call #2 happened (full notes: `research/calls/2026-04-02_concept.md`)
- **[CLI]** Thao (16:42 CEST, post-call): shared client-facing **Figma file** (`figma.com/design/KJ28O0OgMuHPmzBexBVwcn/Share--web--client-`) with: static concept, website structure, homepage wireframe. Asked for feedback via Figma comments to keep everything in one place. Attached Keynote presentation with the animations shown on call.
- **[CLI]** Share team (16:43): *"Awesome - thank you Thao! We'll sit down over the weekend to go through all this and provide some feedback"*
- **[INT]** Miroslav: shared `youtube.com/shorts/GwKuFREOgmo`

## 2026-03-31

- **[CLI]** Thao: proposed call for tomorrow (Apr 1) or Thursday (Apr 2) afternoon for concept sync.
- **[CLI]** Share: tomorrow fully booked, Thursday Apr 2 at 2pm East Africa Time confirmed.
- **[CLI]** Share (later): traveling, schedule shifted, important in-person meeting at 2pm — pushed to 4pm EAT same day. Thao confirmed.

## 2026-03-30

- **[CLI]** Jose (12:30 CEST): shared **Google Drive folder** with images and video from Kenya deployments — `drive.google.com/drive/folders/19Mtm6W9RpvwqQhkFIcELxV1sh_4bOKR1`. Contents:
  - Data center setup and equipment
  - Fiber cabling: blue cables branded *"Everyone's Internet"* — key visual to highlight
  - Street-level infrastructure
  - Outdoor micro data centers (white cabinets) installed on telecommunication towers
- **[CLI]** Jose (12:30, REQUIREMENT): *"please anonymize all third-party brands visible across the infrastructure, carrier logos, equipment manufacturers, tower company branding, etc. should all be removed or obscured. Our branding should be the only one featured."*
- **[INT]** Thao: shared the same Google Drive link with Lukáš, asked him to request access via vkz mail.
- **[INT]** Thao: shared the **internal Figma** file (`figma.com/design/JOpXODkZs64LwHyVlIo7at/Share--web--internal-`) with Lukáš.

## 2026-03-26 to 2026-03-27

- **[INT]** (03-26 16:33): Notion bot joined channel; Thao shared the **Notion concept page** — `notion.so/vkz/Concept-1-32f7e6e924a08002afe4f4634d3879d3`. Asked Miroslav to draft copy for the sections/visuals using Claude.
- **[INT]** (03-25 16:55): Thao shared the **FigJam board** — `figma.com/board/Vjzp3FTZGCqoduO2HHAVvI/Share.inc` — to give Lukáš base context on Share before joining the project.
- **[CLI]** Jose (03-26 22:06): shared Instagram references for fiber/light visualization. *"The way they use pre-rendered 3D assets with smooth, elegant scrolling is very much aligned with where we see this going. We want to transmit our message in a way that represents the physical side of what we do, the technical precision, accuracy, and raw power of our technology... our identity is built around the hardware, infrastructure, and devices that make us who we are. Towers, cabinets, fiber, routers, that's our arsenal."* Promised photos in the following days. Mentioned Luis added notes to the Notion page on Share-as-marketplace for the hero.

## 2026-03-25

- **[CLI]** Jose: NDA signed by Share side (PDF shared).
- **[CLI]** Jose: clarification — *"Living Twice, Inc is the Delaware C-Corp (legal entity) // Share is the name of the brand."*
- **[CLI]** Thao (10:39): thanked the team for the *"most detailed inputs we've ever received"* and laid out next steps: concept phase → final structure → 1-2 concept directions → present back. Asked Share to share photos/videos when available.

## 2026-03-22 to 2026-03-24

- **[CLI]** (03-22 20:25): Share kickoff: *"Hello team! We are excited for this coming week work with you"*
- **[CLI]** (03-23): Notion populated by Share — questions for review. *"Notion should be ready for you both to start reviewing and diving in @Thao @Miroslav any questions let us know!"*
- **[CLI]** (03-23): Jose shared design reference: `toptier.relats.com`
- **[CLI]** (03-23 16:57): Jose: *"is the NDA something you'll be sharing or should we be sharing from our end?"* — agreed Share would send their version.
- **[CLI]** (03-24 08:14-17): Jose shared 5 Instagram references for fiber/light/glass visualization (*"this is how light travels across each little glass hair demonstrated through a bigger glass tube"*).
- **[CLI]** (03-24 18:50): Jose acknowledged VKZ's NDA draft, said he'd return signed version next morning.
