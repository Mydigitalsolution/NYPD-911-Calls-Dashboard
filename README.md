# Data Apex: NYPD 911 Calls Analysis

A data analytics case study examining NYPD 911 call volume, workload distribution, and response efficiency across New York City boroughs — built to support FY2026 emergency response budgeting and resource allocation decisions.

**Authors:** Ingrid Razemba, Delight Marumani, Simbarashe Razemba

## Project Overview

NYPD receives the largest share of emergency response funding in New York City, yet is overloaded with a high volume of **non-criminal** 911 calls that could be handled by other responders (EMS, FDNY, social services, community teams). This project analyzes NYPD 911 call data from 2023–2024 to quantify that workload imbalance and recommend data-driven strategies for call diversion, staffing, and resource allocation.

### Project Sponsor
**Sarah Thompson** — Director of Emergency Management, NYC Emergency Management (NYCEM)
Responsible for emergency response planning and resource allocation across responder agencies.

### Pain Point
- NYPD is overloaded with 911 calls, especially non-criminal ones.
- NYPD receives the most funding among responder agencies but often overspends.
- NYCEM lacks the data needed to rebalance responder workloads across agencies.

### Why It Matters
The sponsor needed visibility into:
- The true workload placed on NYPD
- How many calls could be redirected to EMS, FDNY, or social services
- How call patterns affect FY2026 budgeting
- Opportunities to reduce NYPD burnout and improve response efficiency

## Objectives

- Identify patterns in NYPD-handled 911 calls
- Determine which call types require non-police responders
- Support FY2026 budget decisions with data
- Reduce NYPD workload by diverting non-criminal calls
- Improve coordination across responder agencies (NYPD, FDNY, EMS, etc.)

## Methodology

**Data source:** NYPD 911 call records (2023–2024)

**Approach:**
1. Cleaned and categorized call types
2. Aggregated call data by borough, hour, and month
3. Computed key KPIs: Load Index, Repeat Caller Rate, Handling Time
4. Identified inefficiencies and operational bottlenecks

**Tools:** Tableau (visualization and KPI dashboards)

## Key Findings

### Call Volume Composition
- **93% of all 911 calls are non-criminal** — the top 10 most frequent call types include only 3 criminal categories (led by *Visibility Patrol* and *Investigate Possible Crime*).

### Borough Workload Imbalance
- **Brooklyn** and **Manhattan** handle the highest call volumes.
- **Bronx** and **Queens** have similar volumes, roughly 1.5 million fewer calls than Brooklyn/Manhattan.
- **Staten Island** receives the fewest calls.
- **The Bronx is the most overloaded borough**, with a Load Index of 2.1 and an average handling time of 41 minutes — far above other boroughs — and crime-related calls there take the longest of any call type to resolve.

### Time Patterns
- **Peak months:** March, May, and October — spikes align with holidays/events (St. Patrick's Day, Mother's Day/Memorial Day/Cinco de Mayo, Halloween).
- **Peak hours:** 4–6 PM daily; 4 AM sees the fewest calls.

### Handling Time
- Most call types (vehicle accidents, larceny, robbery, IAB, assault) are resolved in a **median 60–90 minutes**.
- **Rotational tows** and **suspect holding** require significantly longer, consuming disproportionate operational resources.

## Recommendations

| Recommendation | Description |
|---|---|
| **Multi-Agency Response System (MARS)** | Divert wellness, domestic, and low-risk calls to EMS, social services, and community response teams |
| **Community Awareness Campaign** | Educate residents on when to use 311 (non-emergency) vs. 911 |
| **Reallocate Resources to High-Demand Boroughs** | Add a new patrol or redistribute officers, with priority focus on the Bronx |
| **Time-Based Staffing** | Align scheduling with identified hourly and seasonal peaks |
| **Improve High-Duration Call Types** | Streamline rotational tow and suspect-holding workflows, including AI-enabled triaging |

## Conclusion

NYPD's workload is dominated by non-criminal calls, and clear borough-based workload imbalances exist — particularly in the Bronx. Efficient emergency response requires strategic resource allocation and a multi-agency approach to reduce NYPD overload. Better call triage translates directly into faster response times and improved community safety, giving NYCEM the evidence base needed for smarter, fairer FY2026 budgeting and operational planning.

## Repository Contents

```
.
├── Data_Apex_Dashboard_Presentation.pptx   # Full presentation deck with dashboard visuals
└── README.md
```

The presentation includes Tableau dashboard screenshots covering:
- Calls by Borough (map view)
- Calls Handled by Patrol Borough
- Call Type Volumes
- Call Volume by Month and by Hour
- Handling Time breakdowns (overall and Bronx-specific)
- Consolidated KPI dashboard

## Tools & Technologies

- **Tableau** — data visualization and interactive KPI dashboards
- **NYPD Open Data** — source 911 call records (2023–2024)
