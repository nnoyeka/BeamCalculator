# BeamCalculator

Simple calculator built with Python and Django to assis with steel beam design to Eurocodes 3.
Takes span, dead load, live load, steel grade and support conditions as input. Recommends the most efficient UB section from a steel section library and displays calculation sheet with clause references, utilisation ratios and bending moment/shear force diagrams.
ML powered section recommender trained on synthetically generated EC3 calculation data.

# Eurocode References
EC0 EN 1990 - load combinations
EC3 EN 1993-1-1 - steel beam design
Section properties sourced from SCI Steel Blue Book
