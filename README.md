# FlightDataAnalytics
Dataset & Core Features
The dataset contains 12 key features capturing the complete travel profile:

Operational Attributes: airline (Vistara, Air India, IndiGo, SpiceJet, AirAsia, GO FIRST), flight code, source_city, and destination_city (covering Delhi, Mumbai, Bangalore, Kolkata, Hyderabad, and Chennai).

Schedule Attributes: departure_time and arrival_time segmented into six daily time blocks, stops, and total duration (0.83 to 49 hours).

Commercial Metrics: Travel class (Economy vs. Business), days_left before departure (1 to 49 days), and ticket price (₹1,005 to ₹1,23,000).

Key Findings

Class & Carrier Disparities: Travel class is the single largest price driver. Economy fares average ₹6,572, while Business class averages ₹52,540. Only Vistara and Air India offer Business class in this dataset, leading to substantially higher overall carrier averages (~₹30,000 and ~₹23,500) compared to budget carriers like AirAsia (~₹4,000).

Lead Time Volatility: Fares surge dramatically when booked within 1 to 4 days of departure (~₹30,000 average) and flatten into predictable baselines when booked 20 to 49 days in advance (~₹18,000 average).

Temporal & Route Patterns: Peak flight departures occur in the Morning, while arrivals peak at Night. Delhi represents the highest-volume origin city, and Mumbai serves as the top destination. Night departures and evening arrivals consistently command higher average fares than late-night flights.

Technical Stack
Implemented entirely in Python using Pandas and NumPy for data cleaning, aggregation, and statistical filtering, alongside Matplotlib and Seaborn for multi-variable categorical and relational visualizations.
