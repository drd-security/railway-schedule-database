# Database design

The project models a railway/public-transport timetable inspired by GTFS concepts. The conceptual design was developed before the implementation stage and includes agencies, routes/itineraries, stops, services, trips, served stops, schedules, languages, and service exceptions.

The relational implementation uses primary/foreign keys, integrity checks, cascading rules, recursive date generation, and analytical SQL views. The schema was reviewed in the original coursework for normalization, including BCNF considerations.
