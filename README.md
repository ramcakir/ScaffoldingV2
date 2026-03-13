SteigerCalc Pro - Scaffolding Cost Estimator
A professional Progressive Web App (PWA) for calculating fixed scaffolding costs for large construction projects, based on Western European pricing standards.

Features
Real-time Cost Calculation: Instant updates as you modify dimensions and rates
Editable Unit Rates: Customize assembly, disassembly, and rental rates per m3
Project Management: Save and load projects as JSON files
Export Options: Export to CSV for spreadsheet integration
Print Support: Generate professional cost reports
Offline Capable: Works without internet connection (PWA)
Responsive Design: Optimized for desktop and mobile devices
Pricing Model
Based on Q1 2026 Western European market rates:

Component	Rate                	Recommended Range
Assembly	EUR 18.67/m3        	10-20 EUR/m3
Disassembly	EUR 18.67/m3	      Equal to assembly
Weekly Rental	EUR 0.41/m3/week	0.30-0.70 EUR/m3/week

Calculation Formulas
Volume (m3) = Length × Width × Height × Quantity × Factor
Assembly Cost = Volume × Assembly Rate
Disassembly Cost = Volume × Disassembly Rate
Rental Cost = Volume × Rental Rate × Period (weeks)
Total Cost = Assembly + Disassembly + Rental
