# Aviation Accident Analysis


**What I did**
- Loaded a CSV, cleaned it, made `fatal_serious_rate` and `destroyed`.
- Looked at small (<20) vs large (≥20) planes.

**Findings**
- Weather: IMC worse than VMC — fatal/serious ~61.7% vs 23.7%; destroyed ~34.6% vs 7.2%.
- Phase: highest MANEUVERING 36.0%, CLIMB 31.8%; lowest LANDING 0.9%, TAXI 1.7%.
- Large planes: lower injury fractions; small planes: more spread.

**Run**
1) Put `data/AviationData.csv`  
2) Run cleaning → makes `data/aviation_clean.csv`  
3) Run analysis (plots in the notebook)

*Note: based on accidents only. 