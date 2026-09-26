This project analyzes 3.87M+ battery swap events across VoltRelay Energy’s six-city network (Jan 2024 – Jun 2025).
Focus areas:

Reliability & failure rates

Customer abandonment behavior

City & infrastructure variation

Queue waiting times

Revenue trends

⚡ Key Findings
Failure spikes: May–Jun 2024 & May–Jun 2025

City differences: Jaipur (5.06%), Delhi NCR (4.71%), Hyderabad (4.27%) higher than others

Charger generation: Gen1 had highest failure rate (4.64%) vs Gen2 (2.99%) & Gen3 (3.01%)

Queue wait impact: Abandonment rises sharply after 10 minutes (up to 60% at 20–40 min)

Failure types: “No charged battery” failures (134K) >> system errors (11K)

Revenue growth: ₹233 Cr+ recorded, increasing with transaction volume

📂 Dataset Summary
swap_events.csv – 3.87M rows (primary transaction data)

stations.csv – 152 stations (city, zone, charger attributes)

riders.csv – 20K riders (vehicle attributes)

batteries.csv – 6.5K batteries (lifecycle/health)

station_hourly_status.csv – 1.48M rows (operational status)

support_tickets.csv – 44K tickets (customer issues)

city_daily_context.csv – 3.2K rows (weather/grid context)

fleet_partners.csv – 12 partners

🚀 Business Recommendations
Prioritize high-failure stations for investigation

Improve charged-battery availability (inventory & replenishment)

Reduce queue waits >10 min with alerts & interventions

Investigate Gen1 stations (maintenance, upgrades)

Build continuous monitoring dashboards (city/station/hour KPIs)

⚠️ Limitations
Observational analysis (associations ≠ causation)

City, station, charger generation & demand may interact

Further scope: battery suppliers, support tickets, rider retention, pricing, weather impact

✅ Conclusion
The analysis highlights failure spikes, city-level differences, Gen1 charger issues, and queue wait-driven abandonment as the strongest operational signals.
