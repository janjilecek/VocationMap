Vocation Map: Linking Social Media-Predicted Personality Traits and
Occupations
================

This repository contains code and data accompanying the publication
“Social Media-Predicted Personality Traits Can Help Match People to
their Ideal Jobs” \[Kern et al,
    PNAS’20\].

# Reference:

    [Kern et al, PNAS'20] Kern, M. L., McCarthy, P. X., Chakrabarty, D., & Rizoiu, M.-A. (2020). Social Media-Predicted
    Personality Traits Can Help Match People to their Ideal Jobs. Proceedings of the National Academy of Sciences.

# Repository content:

This repository contains the following code scripts:

  - `scripts/prediction-step1-run-prediction.sh`
  - `scripts/prediction-step2-read-prediction-models-from-Python.R`
  - `scripts/prediction-step3-plot-prediction.R`
  - `scripts/predict-profession-python.ipynb`
  - `scripts/utils.R`
  - `scripts/vocation-map.R`

The following data and plots is also available:

  - `data/profession-profiles.csv` – contains the psychological profiles
    for each occupation in the VocationMap.
  - `plots/professions-explore-20-cluster.pdf` – a static version of the
    Vocation Map. Find an interactive version of this map at
    <http://bit.ly/vocation-map-interactive> .

![A static version of the Vocation
Map.](plots/professions-explore-20-cluster.png)

# Additional data file:

The following files cannot be publicly shared due to the Twitter’s and
IBM Watson’s Terms of Service. However, these files could be provided
privately upon request, requests are evaluated at a case-by-case basis.

  - `data/uniq_data.csv` – contains the Big5 and the personal values (10
    features) for every user in the occuaption prediction part of the
    paper;
  - `data/uniq_data_big5.csv` – contains solely the Big5 traits for the
    users above (useful for the ablation study);
  - `data/uniq_data_values.csv` – contains solely the personal values
    for the users above (useful for the ablation study).

# License

Both data set and code are distributed under the General Public License
v3 (GPLv3) license, a copy of which is included in this repository, in
the LICENSE file. If you require a different license, please contact us
at <Marian-Andrei@rizoiu.eu>
