This repository contains the data and documentation related to a research paper titled "The Great Talent Divergence: Transnational Training and the Fate of China’s Doctoral Elite (1905-1962)", to appear in *Modern China*. 

# Abstract

This research investigates the trajectories of over 4,600 Chinese PhD holders trained abroad between 1905 and 1962, drawing on dissertation catalogs compiled by bibliographer Yuan Tongli (1895–1965) and supplemented with biographical data drawn from the [Chinese University Students Dataset (CSUD-OS)](https://leecampbellgroup.blog/projects/china-university-student-dataset-cusd-project/), the [Modern China Biographical Database](https://heurist.huma-num.fr/ModernChinaBiographicalDatabase/web/109237), as well as online sources like Wikipedia and Baidu, subjected to historian's critical scrutiny. Through a mixed-method approach combining statistical analysis, data visualization, and micro-portraits, it shows how these scholars’ educational paths and careers were shaped by national priorities, geopolitical turmoil, and the ascent of U.S. academic dominance, and how the Communist Revolution fractured them irrevocably. While some found their place in the People’s Republic of China, the vast majority faced harsh repression or remained in exile. The findings challenge nationalist narratives of intellectual return: rather than a story of homecoming, this is one of exile, repression, and survival. Only a minority found a place in the People's Republic; the vast majority faced persecution, displacement, or permanent estrangement from their homeland. By offering the first empirical assessment of the large-scale damage inflicted on intellectual elites during the Maoist era, this research lays the groundwork for a more rigorous reevaluation of transnational intellectual mobility and its entanglement with authoritarianism and academic freedom across political regimes.

# Research Questions

This study explores three sets of progressively expanding questions: 

1. Where did the first Chinese PhDs complete their doctoral research, in which disciplines, and which topics did they choose to study? How did this geographical and topical map of knowledge production evolve during the first half of the twentieth century, marked by global wars and regime changes in China?
2. Where did they come from? What were their generational, geographical, and educational backgrounds? Where did they receive their training before going abroad for doctoral research?
3. How did their careers unfold after graduation? What happened to them after the Communist Revolution? How many left, and how many stayed? How did their careers diverge after 1949, and what factors (generation, disciplinary grounding, political antecedents during the Republican era) shaped their post-1949 trajectories?

# Repository Structure

This repository is structured into three folders:

1. **Data** – contains the master datasets (aggregated lists of theses across regions, biographical data on PhDs) as well as the sub-datasets created during the analyses ('.RData' files).
2. **Scripts** – contains the R scripts used to analyze the theses and the biographical trajectories of individuals ('.Rmd' and '.html' files).
3. **Media** – contains various visualizations produced for exploratory purposes in the course of the analysis.

The data and scripts folders each contain three sets of files corresponding to the three stages of the research:

  - (1) Analysis of [dissertations](https://bookdown.enpchina.eu/YTL_phds/phd1.html),
  - (2) Analysis of [PhD backgrounds](https://bookdown.enpchina.eu/YTL_phds/phd2.html),
  - (3) Analysis of [post-graduation careers and post-1949 fate](https://bookdown.enpchina.eu/YTL_phds/phd3.html).

# Acknowledgements
This research was funded by the European Research Council (ERC) under the European Union’s Horizon 2020 Research and Innovation Programme (Grant Agreement No. 788476) and by the Chiang Ching-kuo Foundation for International Scholarly Exchange (Project No. RG004-U-21). The authors also wish to express their gratitude to the Lee–Campbell Research Group for generously sharing their datasets.
