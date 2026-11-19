# Senior-Targeted Software/Platform Startups: Global and Korean Case Studies, Business Models, and Who Pays

Research date: 2026-11-19. Scope: US, Japan, Europe/UK, Korea. Budget-limited pass (about 16 tool calls), so many items below are flagged as gaps. Facts from secondary aggregators are marked as such. Company-reported numbers are labeled "(company claim)".

---

## 1. Who pays? User vs. buyer (senior vs. adult child vs. B2B / B2G)

### Takeaway
The buyer is almost never the senior alone. The scaled winners are paid by institutions: Medicare Advantage plans (Papa), home-care agencies (Birdie, AlayaCare, WellSky, Kanamic), long-term care insurance reimbursement (Korean 방문요양 operators such as 케어링), and government aging agencies or Medicaid (ElliQ). The adult-child or caregiver population is large and under strain, but the evidence that it reliably pays out of pocket for software is weak. Treat caregivers as the people who choose and set up the product, and look for an institution to fund it.

### Cited Findings
- **US caregiver base (Caregiving in the US 2025, AARP + National Alliance for Caregiving, July 2025):**
  - 63 million family caregivers, about 1 in 4 US adults, up 45% (nearly 20 million) over a decade.
  - About 1 in 4 provide 40+ hours of care per week.
  - About 20% report fair or poor health caused by caregiving.
  - Half report a negative financial impact, a quarter are taking on debt, and 1 in 5 cannot afford basic needs.
  - 29% are "sandwich generation" (caring for both children and adults); this rises to 47% among caregivers under 50.
  - Almost 40% say respite services would help.
  - Data come from a nationally representative Ipsos online panel.
  - Sources: [AARP press release 2025-07-24](https://www.aarp.org/press/releases/2025-07-24-new-report-reveals-crisis-point-for-americas-63-million-family-caregivers.html); [AARP survey page](https://www.aarp.org/caregiving/basics/caregiving-in-us-survey-2025/); [AARP PPI report](https://www.aarp.org/pri/topics/ltss/family-caregiving/caregiving-in-the-us-2025/)
- **State spread:** the share of adults who are caregivers ranges from 20% (DC) to 34% (Mississippi) — [AARP state caregiver report 2025](https://www.aarp.org/caregiving/basics/state-caregiver-report-2025/)
- **Follow-up data on financial strain (Oct 2025)** — [AARP press release 2025-10-28](https://www.aarp.org/press/releases/2025-10-28-new-data-expose-financial-strain-of-family-caregiving/). The detailed figures were not fetched.
- **Papa (B2B2C, payer = health plans):** Papa began working with Medicare Advantage (MA) plans in 2020, one year after CMS let MA plans cover "social needs" as supplemental benefits. Star-rating bonus payments give plans a financial reason to buy engagement services. — [KFF Health News, 2022](https://kffhealthnews.org/news/article/medicare-advantage-plans-senior-companions-profits/)
  - Papa reportedly works with more than 40 health plans and has facilitated more than 3 million in-home visits (company claim, via aggregator) — [aggregator summary](https://loud-particle-7d0.notion.site/He-turned-his-grandad-s-loneliness-into-a-1-4B-business-then-almost-lost-the-lot-3aa8d2b9402b80909c73d3cda3cc6452)
- **Honor (B2B, revenue share with agencies):** Honor's technology takes over billing, scheduling, staffing and other back-office work for agency partners in exchange for a negotiated share of their revenue. — [Honor/Home Instead coverage via search summary](https://www.darwinresearch.com/news-and-insights/our-take-honor-technologies-acquires-home-instead-with-goal-of-scaling-up-high-quality-senior-home-care-n0ccd)
- **ElliQ (B2G / payer channel, not D2C):**
  - Intuition Robotics said its $25M round would serve demand from government aging agencies and healthcare organizations — [MobiHealthNews](https://mobihealthnews.com/node/153372)
  - A secondary profile describes ElliQ's target channel as institutional (payors and operators). The same profile reports that Washington State Medicaid covers ElliQ as a "Smart Care Device" (reported March 2026; not verified against a primary state source). — [robotics.press](https://www.robotics.press/news/intuition-robotics-company-profile/)
- **Care-agency SaaS (B2B):** Birdie charges agencies a subscription software licence — [Dealroom](https://dealroom.co/companies/birdie/)
- **Korea (payer = 노인장기요양보험 reimbursement):** 케어링's core 방문요양 and 주간보호 business is reimbursed through long-term care insurance. Its commerce division sells 복지용구 (welfare equipment, partly reimbursed) and PB goods. — [Byline Network, 2026-05](https://byline.network/2026/05/08_12093874/)
- **Japan (payer = 介護保険 agencies and municipalities):** Kanamic's main segment is a cloud platform for medical and nursing-care providers — [JPX tanshin FY2025](https://www2.jpx.co.jp/disc/39390/081220251113599636_tse-acedjpsm-39390-20251113339390-ixbrl.htm)
- **Japan 見守り:**
  - A 2013 study found low uptake of monitoring services among seniors living alone. Uptake and intent were higher for emergency-response services than for routine safety checks, and higher among people with a medical history. — [JSPH 2013](https://www.jsph.jp/docs/magazine/2013/05/60-5_285.pdf)
  - Yokohama city materials show electricity-usage monitoring bundled with insurance against solitary death (孤独死). This is a bundled-insurance funding model. — [Yokohama city PDF](https://www.city.yokohama.lg.jp/business/bunyabetsu/kenchiku/torikumi/safetynet/safety-mimamori.files/0108_20261007.pdf)

### Inferences
- The pattern is "senior = user, family = influencer and onboarder, institution = payer." Every scaled case in this pass with known revenue has an institutional or insurance payer: Papa, Honor, Birdie, AlayaCare, Kanamic, and 케어링 (LTC insurance). None of the verified scaled cases is mainly funded by adult children paying for a software subscription.
- The AARP financial-strain data (half see a negative financial impact, a quarter are in debt) suggests caregivers have limited room to pay more for software. Their "willingness to pay" is better captured indirectly:
  - employer benefits (salaried workers already have better access to caregiving benefits, per AARP)
  - insurer bundles
  - service marketplaces where software is the wrapper around paid care hours
- In Japan, families show more willingness to pay for emergency-response monitoring than for "nice to have" daily check-ins. A small team should frame products around acute risk (falls, disappearance, 孤独死) or around a reimbursed workflow.

### Gaps
- No quantitative willingness-to-pay study (US, Japan or Korea) was retrieved for adult-child subscriptions, for example monthly price tolerance for monitoring or companion apps.
- No Korean equivalent of the AARP caregiving survey was retrieved (for example a 보건복지부 노인실태조사 or 가족돌봄 survey with spending data).
- B2B buyers such as banks, employers and insurers in Korea (for example 보험사 제휴 senior services) were not researched in this pass.

---

## 2. Successful cases and metrics (2022–2026)

### Takeaway
The most durable metrics belong to "boring" B2B workflow software for care providers (Kanamic in Japan is profitable and listed; AlayaCare and Birdie raised large rounds) and to reimbursed service operators that use tech internally (케어링: 165.8B KRW revenue in 2025). Consumer and companion plays show user counts but little disclosed revenue.

### Cited Findings

**Japan: Kanamic Network (カナミックネットワーク, TSE Prime 3939)**
- FY2025 (ended Sep 2025):
  - Revenue ¥5,500M (+9.9%)
  - Operating profit ¥1,606M (+11.6%), about a 29% operating margin
  - EBITDA ¥2,024M (+12.8%)
  - Net profit ¥1,111M (+20.8%)
  - Medical and nursing-care cloud platform segment: revenue ¥3,580M, profit ¥1,490M
  - Franchise openings slowed from 3 in FY2024 to 1 in FY2025
  - Source: [JPX tanshin FY2025, 2025-11-13](https://www2.jpx.co.jp/disc/39390/081220251113599636_tse-acedjpsm-39390-20251113339390-ixbrl.htm); [logmi Finance](https://finance.logmi.jp/articles/383212)
- FY2026 (ended Sep 2026, tanshin dated 2026-11-13): the search snippet showed net sales of ¥7,804M. **Unverified.** It is a partial table fragment, and a jump of about 42% may reflect an acquisition. Check the [FY2026 tanshin](https://www2.jpx.co.jp/disc/39390/081220261113579807_tse-acedjpsm-39390-20261113339390-ixbrl.htm) directly.

**Korea: 케어링 (Caring)**
- 2025 consolidated revenue 165.8B KRW, a record.
- Monthly EBITDA turned positive in Nov 2025.
- Series C of 40B KRW closed in early 2026; cumulative funding about 115B KRW.
- Investors cited its standardized directly operated (직영) branch model.
- Employs 10,000+ 요양보호사 and 사회복지사; cumulative wages paid exceed 300B KRW.
- Sources: [Byline Network](https://byline.network/2026/05/08_12093874/); [Hankyung Magazine 2026-05](https://magazine.hankyung.com/job-joy/article/202605083812d); [VentureSquare](https://www.venturesquare.net/1120859/)

**Korea: 케어닥 (Caredoc)**
- Series B of 17B KRW (Nov 2023); cumulative 31.5B KRW — [Unicorn Factory 2023-11](https://www.unicornfactory.co.kr/article/2023111509372038006)
- Oct 2025: secured 31B KRW through senior-housing project financing (PF, not equity) tied to its operated premium housing brand "케어홈 프리미오." This is a pivot toward housing and facility operation, beyond the original caregiver-matching platform. — [Unicorn Factory 2025-10-21](https://www.unicornfactory.co.kr/article/2025102112504945843)
- A VentureSquare headline cites "투자유치 530억원·시니어하우징 PF 1000억원대" (53B KRW raised, senior-housing PF in the 100B KRW range). The full article was not fetched. — [VentureSquare](https://www.venturesquare.net/1120108/)
- 2025 revenue: not found (paywalled on THE VC) — [THE VC](https://thevc.kr/caredoc)

**Korea: 한국시니어연구소 (Korea Senior Lab, brand 스마일시니어)**
- Founded June 2019.
- Seed 400M KRW (Spring Camp, Bon Angels); follow-on 860M KRW; Series A 11B KRW (2021).
- Monthly revenue of about 200M KRW at that time (2021, company claim).
- Model: directly operated and franchised 방문요양 branches; reported "300호점" (300 branches) milestone.
- Sources: [Wowtale 2020](https://wowtale.net/2020/01/02/kslab-raised-seed-funding/); [Unicorn Factory 2021](https://www.unicornfactory.co.kr/article/2021102916241623422); [THE VC](https://thevc.kr/koreaseniorlab)

**Korea: 시놀 (Sinor, 5060+ social and activity app)**
- Members grew from about 20,000 (end 2023) to about 100,000 (end 2025) (company claim).
- Seed investment from AUM Ventures (June 2023), amount undisclosed.
- Mostly users in their 60s; 70% male (2024 report).
- No revenue disclosed.
- Sources: [THE VC](https://thevc.kr/sinor); [Asiae 2023](https://view.asiae.co.kr/article/2023070216183295603); [Tech42](https://www.tech42.co.kr/?p=73114)

**Korea: 요양이 (AI senior-care matching platform)**
- Revenue rose from 0.2B KRW (2024) to 0.77B KRW (2025); pre-A round from 뉴패러다임인베스트먼트 — [Unicorn Factory 2026-01](https://www.unicornfactory.co.kr/article/2026010815315640285)

**US: Papa**
- $150M Series D at a $1.4B valuation (Nov 2021), the last public valuation — [MedCity News](https://medcitynews.com/2021/11/senior-care-startup-papa-valued-at-1-4b/); [MobiHealthNews](https://www.mobihealthnews.com/news/senior-care-platform-papa-scoops-150m-series-d-funding)
- Papa claims a 9% reduction in cost of care for engaged MA members (company claim, not independently verified) — [Fierce Healthcare](https://www.fiercehealthcare.com/payers/papa-more-closely-align-insurers-promising-cost-reductions)
- 97% visit fill rate in 2025 (company claim via aggregator) — [aggregator](https://loud-particle-7d0.notion.site/He-turned-his-grandad-s-loneliness-into-a-1-4B-business-then-almost-lost-the-lot-3aa8d2b9402b80909c73d3cda3cc6452)

**US: Honor / Home Instead**
- Honor acquired Home Instead (franchise network) on 2021-08-06; the combined business had more than $2.1B in home-care services revenue (2021 figure) — [Senior Housing News](https://seniorhousingnews.com/2021/08/06/honor-acquires-home-instead-in-home-care-deal-with-senior-living-implications/); [HealthExec](https://healthexec.com/topics/healthcare-management/healthcare-economics/homecare-acquisition-creates-2b-business)
- Earlier $70M venture plus $300M debt financing — [MobiHealthNews](https://www.mobihealthnews.com/news/senior-care-tech-company-honor-scores-70m-venture-dollars-300m-debt-financing)

**US: CareLinx (caregiver marketplace)**
- Acquired by Generali Global Assistance (2017) — [MobiHealthNews](https://www.mobihealthnews.com/news/caregiver-startup-carelinx-acquired-generali-global-assistance)
- Then acquired by Sharecare (2021) for about $65M ($54.6M cash + $10.4M stock) — [HIT Consultant 2021](https://hitconsultant.net/2021/08/11/sharecare-acquires-carelinx)
- Its buyers were insurance and assistance companies and a digital-health platform, not consumers.

**Canada / global: AlayaCare (home-care agency SaaS)**
- Series D in 2021, reported as CAD $225M led by Generation Investment Management — [BusinessWire](https://www.businesswire.com/news/home/20210623005361/en/AlayaCare-Raises-%24225-Million-to-Accelerate-the-Digital-Transformation-of-Home-Health-Care)
- $50M growth capital facility from CIBC Innovation Banking (Feb 2026) — [BuiltIn](https://builtin.com/articles/alayacare-secures-50m-20260219)
- Acquired Nightingale (Oct 2025); cumulative funding estimated at $274–282M (aggregators conflict) — [Clay](https://clay.com/dossier/alayacare-funding)

**UK: Birdie (home-care agency SaaS)**
- Series B of about $30M (2022, Sofina-led); cumulative about $52M (another source: £42.8M) — [Just Entrepreneurs](https://justentrepreneurs.co.uk/news/birdie-raises-30m-series-b-to-transform-elderly-care-at-home); [BusinessCloud](https://businesscloud.co.uk/news/birdie-raises-25m-to-transform-elderly-care-at-home/)
- Claims 1,000+ providers and 60M+ visits per year (company claim) — [Welcome to the Jungle](https://app.welcometothejungle.com/companies/Birdie)
- Revenue estimates conflict widely, and Preqin's figure looks stale — [Preqin](https://www.preqin.com/data/profile/asset/birdie-care-services-limited/302781)

**ElliQ (Intuition Robotics)**
- Total equity about $81–85M.
- Kanematsu took a strategic minority stake (Sep 2025) for a planned Japan launch in 2026.
- Source: [The Robot Report](https://www.therobotreport.com/intuition-robotics-partners-with-kanematsu-to-bring-elliq-to-japan/)

**GrandPad (senior tablet)**
- Minneapolis-based; Home Instead is an investor and partner. CB Insights calls it a "subsidiary of Home Instead," which is unverified and conflicts with Wikipedia — [Wikipedia](https://en.wikipedia.org/wiki/GrandPad); [CB Insights](https://www.cbinsights.com/company/grandpad)

### Inferences
- **Two winning archetypes for small Korean teams:**
  - (a) Vertical SaaS for reimbursed care providers. The Kanamic, Birdie and AlayaCare type in Korea would target 방문요양센터, 주간보호센터 and 요양원, all funded by 장기요양보험. Kanamic's roughly 29% operating margin shows this can be very profitable once embedded.
  - (b) A tech-enabled reimbursed-service operator (케어링, 한국시니어연구소). This needs capital and labor operations, which is a poor fit for 1–5 people.
- Korean consumer-social plays (시놀) show user growth but no disclosed monetization. This is the classic senior-direct pattern: engagement is achievable, revenue is not.
- 케어닥's move toward senior housing PF suggests that pure platform or marketplace revenue (caregiver matching) was not sufficient on its own. This is an inference; the company has not said so.

### Gaps
- No verified data on: Lotsa Helping Hands, CaringBridge (nonprofit, donation-funded), Carely, LIFULL介護, SOMPO's 介護 DX (e.g., egaku), 보살핌, 그레이스케일, WellSky/ClearCare revenue.
- Honor's 2024–2026 revenue was not found.
- Papa's 2024–2026 revenue and valuation were not found.

---

## 3. Notable failures, pivots and reasons

### Takeaway
Failures cluster around four problems:
- labor-intensive marketplaces with trust and safety risk (Papa)
- capital-heavy pivots from tech to operating services (Honor's restructuring)
- hardware companions with weak unit economics (the robotics category)
- low-uptake consumer monitoring (Japan 見守り)

### Cited Findings
- **Papa safety and controversy:**
  - Bloomberg (May 2023) reported serious safety complaints.
  - New York insurer CDPHP halted all in-person Papa visits after an incident between a "Papa Pal" and a member.
  - The US Senate Aging Committee wrote to CMS asking about the safety and quality of Papa's services.
  - Papa responded with stronger background checks and trust and safety advisers.
  - Sources: [AIS Health](https://aishealth.mmitnetwork.com/blogs/health-plan-weekly/experts-urge-strict-vendor-vetting-amid-reports-of-trouble-with-papa-pals); [AIS Health news brief](https://aishealth.mmitnetwork.com/blogs/radar-on-medicare-advantage/news-briefs-new-york-insurer-raises-red-flag-about-in-home-visits-from-papa-pals); [Senate Aging letter to CMS](https://www.aging.senate.gov/imo/media/doc/letter_to_cms_re_papa_inc.pdf)
- **Papa layoffs:** employee-reported layoffs in July 2022 and August 2023 (about 25 people). None were found for 2024–2025. No valuation update since 2021. — [TrueUp](https://trueup.io/co/papa-senior)
- **Papa business-model critique:** KFF argues MA plans buy companionship partly to improve star ratings, bonuses and profits. That ties Papa's revenue to MA policy risk. — [KFF Health News](https://kffhealthnews.org/news/article/medicare-advantage-plans-senior-companions-profits/)
- **Honor restructuring:** in June 2023 it cut about 15% of headquarters staff to streamline after the Home Instead acquisition — [AgingHere newsletter](https://aginghere.beehiiv.com/p/jun-30-2023-aginghere-evolving-home-care-honors-restructure-techdriven-approach). An earlier SF Chronicle article reported admin and HR layoffs (date unclear) — [SF Chronicle](https://preview-prod.w.sfchronicle.com/business/article/Layoffs-hit-San-Francisco-care-provider-Honor-14981863.php)
- **Hardware companion robots:** a secondary profile notes that hardware-plus-service eldercare robots have historically struggled with unit economics and reimbursement. ElliQ's response is to sell through institutions rather than to consumers. — [robotics.press](https://www.robotics.press/news/intuition-robotics-company-profile/)
- **Japan 見守り uptake:** low usage rates among seniors living alone; widening adoption was named the core challenge — [JSPH 2013](https://www.jsph.jp/docs/magazine/2013/05/60-5_285.pdf). Dai-ichi Life Research notes that IoT monitoring is designed to avoid burdening seniors who struggle with digital devices, which implies that device-interaction burden is a known failure mode. — [DLRI report](https://www.dlri.co.jp/report/ld/230334.html)
- **Korea:** an analysis notes that agetech devices are multiplying but on-site deployment lags — [Etoday Bravo](https://bravo.etoday.co.kr/view/atc_view/16798)

### Inferences
- For a small team, the Papa lesson is that two-sided human-labor marketplaces bring trust, safety and regulatory liability that software-only products avoid.
- The Honor lesson is that "tech-enabled operator" models need very large capital (Honor raised $300M in debt) and still had to restructure.
- The hardware lesson is to avoid owning devices. Use phones, TVs or KakaoTalk the senior already has, or partner with existing device makers or telcos.

### Gaps
- No documented Korean or Japanese startup shutdown postmortems were retrieved, for example failed senior social apps or failed 見守り ventures.
- The Jibo, Labrador, and Lotsa/Carely trajectories were not verified in this pass.

---

## 4. Distribution channels that work

### Takeaway
Evidence from this pass points to institutional and reimbursed channels: health plans (Papa), agency networks and franchises (Home Instead + GrandPad, Kanamic franchises, 스마일시니어 franchise), government agencies and Medicaid (ElliQ), and municipalities (Japan 見守り pilots). Direct consumer channels (KakaoTalk, YouTube, 복지관, 약국) were not quantified by any source found here.

### Cited Findings
- **Franchise and agency networks as distribution:**
  - Home Instead partnered with GrandPad to provide an integrated care solution — [InsuranceNewsNet](https://insurancenewsnet.com/oarticle/home-instead-senior-care-partners-with-grandpad-to-provide-enhanced-integrated-care-solution)
  - Kanamic runs a franchise channel (openings slowed in FY2025) — [JPX tanshin](https://www2.jpx.co.jp/disc/39390/081220251113599636_tse-acedjpsm-39390-20251113339390-ixbrl.htm)
  - 한국시니어연구소 scaled 스마일시니어 to about 300 branches — [Unicorn Factory hashtag page](https://www.unicornfactory.co.kr/hashtag/%ED%95%9C%EA%B5%AD%EC%8B%9C%EB%8B%88%EC%96%B4%EC%97%B0%EA%B5%AC%EC%86%8C?page=2)
- **Health plans:** Papa reaches seniors through more than 40 health plans — [aggregator](https://loud-particle-7d0.notion.site/He-turned-his-grandad-s-loneliness-into-a-1-4B-business-then-almost-lost-the-lot-3aa8d2b9402b80909c73d3cda3cc6452). It frames "the home as an engagement channel" for plans — [Papa 2026 whitepaper](https://resources.papa.com/hubfs/2026_Imagine%20the%20Papabilities-%20The%20Home%20as%20an%20Engagement%20Channel.pdf)
- **Government:** ElliQ is distributed through state aging agencies — [MobiHealthNews](https://mobihealthnews.com/node/153372)
- **Municipal pilots (Japan):** municipal 見守り pilots aimed to lower adoption barriers and reduce the burden on watchers; Kanagawa and Saitama publish lists of private monitoring providers — [Kanagawa list](https://www.pref.kanagawa.jp/documents/25828/kigyo_all.pdf); [Saitama](https://www.pref.saitama.lg.jp/documents/213537/mimamori_koureisya.pdf)
- **Strategic corporate partner (Japan):** Kanematsu is ElliQ's distribution partner for Japan — [The Robot Report](https://www.therobotreport.com/intuition-robotics-partners-with-kanematsu-to-bring-elliq-to-japan/)

### Inferences
- For Korea, the analogous channels are:
  - 지자체 (municipal 독거노인 돌봄 and 스마트 돌봄 budgets)
  - 장기요양기관 networks (via SaaS or franchise HQs)
  - 보험사 and 카드사 senior benefit bundles
  - Consumer acquisition through KakaoTalk channels targeting the adult child
- This is inference; it was not validated with Korean channel data here.

### Gaps
- No data was retrieved on KakaoTalk, YouTube, 복지관 or 약국 acquisition efficiency (CAC, conversion) for Korean senior services. A separate search is needed, for example 신한라이프/KB 시니어 제휴 or 지자체 AI 돌봄 스피커 사업 (SKT/KT 누구 돌봄).

---

## 5. Product design lessons for senior UX

### Takeaway
The limited evidence found supports "zero-interaction" or passive designs (IoT, electricity-usage sensing, voice) and family- or institution-mediated setup, rather than apps that seniors must learn.

### Cited Findings
- IoT monitoring is valued because it does not burden seniors who are uncomfortable with digital devices — [Dai-ichi Life Research Institute](https://www.dlri.co.jp/report/ld/230334.html)
- Electricity-usage anomaly detection requires no senior action and is bundled with insurance (Yokohama) — [Yokohama city PDF](https://www.city.yokohama.lg.jp/business/bunyabetsu/kenchiku/torikumi/safetynet/safety-mimamori.files/0108_20261007.pdf)
- ElliQ is a proactive voice companion, a voice-first design — [MobiHealthNews](https://mobihealthnews.com/node/153372)
- 시놀 restricts membership to people aged 50 and over ("50세 미만은 출입금지"), a positioning and design choice for peer safety and trust — [Asiae 2023](https://view.asiae.co.kr/article/2023070216183295603)

### Inferences
- For Korea, building on KakaoTalk (알림톡, 챗봇, channel) is likely to beat a native app for both seniors and adult children, because it removes the install step. This was not validated in this pass.

### Gaps
- No usability studies (font size, voice adoption rates, KakaoTalk vs. native-app retention) were retrieved.

---

## 6. AgeTech and longevity investment trends, 2024–2026

### Takeaway
"Longevity" totals are dominated by biotech and are not comparable to AgeTech software. Retrieved figures show a strong 2024 and divergent 2025 numbers that depend on scope. In Korea, capital flowed to reimbursed care operators (케어링 Series C, 40B KRW) and senior housing PF (케어닥), rather than to senior consumer software.

### Cited Findings
- **Longevity.Technology:** 2024 longevity financing was about $8.49B across 331 deals, more than double 2023 — [Lifespan.io](https://lifespan.io/longevity-investment-more-than-doubled-to-8-5bn-in-2024/); [Longevity.Technology](https://longevity.technology/news/longevity-investment-more-than-doubles-as-sector-shifts-focus/)
- **Conflicting 2025 figures (scope differs):**
  - One snippet cites longevity biotech at a record $18.4B in 2025 (a report dated Sep 2026).
  - Another says funding eased to $5.7B in 2025.
  - Money is concentrating in fewer, larger deals.
  - Neither primary report was fetched; treat both as unverified. — [Longevity.Technology investment briefings](https://longevity.technology/investment/); [L.E.K.](https://www.lek.com/insights/life-sciences-pharma/longevity-therapeutics-comes-age)
- **Home-care software:** the global market is estimated at more than $12B (2024), projected near $25B by 2032 (market-research estimate, low reliability) — [Clay/aggregator summary](https://clay.com/dossier/alayacare-funding)
- **Korea, 2025–2026 deals:**
  - 케어링 Series C, 40B KRW (early 2026) — [Byline](https://byline.network/2026/05/08_12093874/)
  - 케어닥 senior housing PF, 31B KRW (Oct 2025) — [Unicorn Factory](https://www.unicornfactory.co.kr/article/2025102112504945843)
  - 요양이 pre-A — [Unicorn Factory 2026-01](https://www.unicornfactory.co.kr/article/2026010815315640285)
  - Innoforest's Q3 2025 healthcare and bio report says investment concentrated in later-stage rounds, with deal size and count down year on year — [Innoforest Q3 2025](https://www.innoforest.co.kr/report/404/2025%EB%85%84-3%EB%B6%84%EA%B8%B0-%ED%97%AC%EC%8A%A4%EC%BC%80%EC%96%B4%EB%B0%94%EC%9D%B4%EC%98%A4-%ED%88%AC%EC%9E%90%EB%8F%99%ED%96%A5-%ED%9B%84%EA%B8%B0%ED%88%AC%EC%9E%90-%EC%A7%91%EC%A4%91%EB%90%98%EB%A9%B0-%EC%9E%91%EB%85%84-%EB%8C%80%EB%B9%84-%EA%B7%9C%EB%AA%A8-%EB%B0%8F-%EA%B1%B4%EC%88%98-%EC%95%BD%EC%A7%84) (summary from the report title)
- **Korea market forecast:** the domestic silver industry is projected to grow from 72T KRW (2020) to 168T KRW (2030), citing 한국보건산업진흥원 — [Etoday Bravo](https://bravo.etoday.co.kr/view/atc_view/16798)
- **Japan:** Kanematsu's ElliQ stake (Sep 2025) shows Japanese trading companies acting as strategic AgeTech investors and distributors — [The Robot Report](https://www.therobotreport.com/intuition-robotics-partners-with-kanematsu-to-bring-elliq-to-japan/)

### Inferences
- Korean capital is rewarding operators with reimbursed cash flow and real-estate-backed models. A 1–5 person software team is unlikely to raise large rounds on a senior-consumer thesis alone. B2B SaaS revenue from 장기요양기관, or a B2G contract, is the more fundable proof point.

### Gaps
- No AgeTech-specific (non-biotech) 2025 global funding total was retrieved, for example from AgeTech Collaborative, Aging2.0 or Crunchbase.
- No THE VC or 혁신의숲 aggregate for the Korean 시니어/실버테크 category was retrieved.
