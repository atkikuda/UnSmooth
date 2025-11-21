# UnSmooth

This repository contains the code used in the paper
"A new approach for correcting the smoothing effect of ordinary kriging estimates" (https: //doi.org/????)

## Abstract
This study introduces a new approach for correcting the smoothing effect inherent to ordinary kriging.
The proposed method performs correction by matching the cumulative distribution of kriging estimates to the empirical
cumulative distribution of the sample data, characterized by the first- and second-order moments.
As a result, the cumulative distribution of the corrected estimates closely reproduces these statistical moments. 
Tests conducted with two datasets demonstrate that the approximation achieves an excellent fit to the empirical cumulative
distribution – both qualitatively, through the improved shape of the corrected distribution, and quantitatively, based on
descriptive statistics, correlation measures, and RMS values. A key advantage of the method is that it requires only a
single processing step, avoiding any post-processing or additional refinement.

The algorithm is provided as a Python script (UnSmooth.py), along with the datasets used in this study, enabling readers
to fully reproduce the presented results.

## License
This program is free software; you can redistribute it and/or modify it under the terms of MPL2 license.
The Source Code Form is subject to the terms of the Mozilla Public License, v. 2.0. If a copy of the MP
L was not %% distributed with this file, You can obtain one at http://mozilla.org/MPL/2.0/.
