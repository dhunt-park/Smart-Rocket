```mermaid
gantt
    dateFormat YYYY-MM-DD
    title Smart Rocket Project Schedule (Autumn Quarter 2027)

    section Term 2 Start
    School Opens :milestone, m1, 2027-04-07, 0d

    section Phase 1: Planning & Design
    Design & Aerodynamics Specs :a1, 2027-04-07, 10d
    Propellant & Math Modeling :a2, 2027-04-07, 10d
    Electronics Schematics :a3, 2027-04-12, 8d

    section Phase 2: Fabrication & Coding
    3D Printing Airframe Components :b1, after a1, 12d
    Avionics & Flight Code Dev :b2, after a3, 14d
    Circuit Assembly & Wiring :b3, after a3, 10d

    section Phase 3: Integration & Testing
    Full Rocket Assembly :c1, after b1, 7d
    Sensor Calibration & Simulation :c2, after b2, 5d
    Static Fire / Ground Tests :c3, after c1, 4d

    section Phase 4: Launch & Analysis
    Pre-Launch Readiness Review :d1, 2027-05-24, 3d
    Target Launch Day :milestone, launch, 2027-05-28, 0d
    Post-Flight Data Analysis :d2, 2027-05-31, 5d
