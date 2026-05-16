# Kenneth Arnold, 1947: Three Agencies, One Event, 75 Years Apart

On June 24, 1947, private pilot Kenneth Arnold reported seeing nine large disk-shaped objects flying in formation near Mount Rainier, Washington at an estimated speed of 1,200–1,700 mph. His account coined the term "flying saucer" and launched the modern UFO era. What has never been publicly reported is this: **at least three separate US government agencies independently documented this event, and their records — spanning 75 years — have never been placed in the same database until now**.

The UAP Knowledge Graph cross-source linker identified two independent corroborations of the Arnold event: AARO ↔ CIA (0 km, 1 day apart) and AARO ↔ Blue Book (0 km, 1 day apart). All three records carry a credibility score of 7.0.

---

## The Three Records

**Blue Book (1947)** — The US Air Force's Project Blue Book logged Kenneth Arnold's report as one of its earliest cases. The record notes a private pilot and businessman sighting nine disk-shaped objects near Mt. Rainier traveling at over 1,000 mph.

**CIA (1947)** — The Central Intelligence Agency independently collected and filed an assessment of the Arnold sighting through its overseas intelligence network and internal analytical apparatus. The CIA record exists in the FOIA reading room, separate from any Air Force file.

**AARO (2022)** — The All-domain Anomaly Resolution Office, established by Congress 75 years after the original event, re-examined the Arnold case as part of its historical UAP review. AARO's record describes the same event: nine large circular objects flying in formation, periodically flipping, with flight characteristics compared to a Chinese kite tail.

---

## What the Cross-Reference Reveals

| Pair | Distance | Days Apart | Score |
|---|---|---|---|
| AARO ↔ CIA | 0 km | 1 day | 7.0 |
| AARO ↔ Blue Book | 0 km | 1 day | 7.0 |

Three agencies. Same location. Same event. Records created 75 years apart — the Air Force and CIA in 1947, AARO in 2022 — and now algorithmically linked for the first time.

---

## The 75-Year Tracking Gap

The most significant finding here is not the original sighting — it is the institutional continuity. The US government has been tracking, re-examining, and re-filing the Kenneth Arnold event across three separate agencies over 75 years. The Air Force investigated it in 1947. The CIA assessed it in 1947. AARO re-examined it in 2022.

No unified assessment has ever been published connecting all three institutional perspectives on the same event. The records exist in three separate archives — the National Archives (Blue Book), the CIA FOIA reading room, and the AARO public case files — with no cross-reference between them.

> The foundational event of the modern UAP era has been continuously tracked across three agencies for 75 years. The unified record has never been published.

---

## Why AARO Re-Examined It

AARO's mandate from Congress was to review all historical UAP records held by the US government and provide a unified assessment. Its 2022 examination of the Arnold case — the same event the Air Force investigated in 1947 — represents the first official attempt to revisit foundational cases with modern analytical tools. That AARO's description matches the 1947 records almost verbatim suggests either remarkable consistency of original documentation, or that AARO's analysts were working directly from the same primary sources.

---

## Explore the Data

Search in the [UAP Explorer](explorer.html): Location **Mount Rainier** · Year **1947** · Shape **disk**.

Or query directly:
```
GET https://uap-knowledge-graph.onrender.com/uap_deploy.json
  ?sql=SELECT * FROM event_links WHERE days_apart<=1
  AND (source_1='AARO' OR source_2='AARO')
  AND distance_km=0 ORDER BY created_at
```

*S. Shilawat · Redefine Zero · May 15, 2026*
*Database snapshot: 266,414 records · 29 sources · 16,086 cross-source links*
