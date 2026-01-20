---
permalink: /
title: "Kai Tang | Academic Homepage"
excerpt: "Ph.D. candidate at BNU, focusing on remote sensing change detection, time-series reconstruction, and agricultural remote sensing"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi! I am **Kai Tang**, a Ph.D. candidate in Cartography and GIS at Beijing Normal University (2022.9–2026.6), advised by Prof. Jin Chen. My work focuses on high-resolution change detection, remote-sensing time-series reconstruction, multi-source data fusion, and agricultural key-parameter monitoring. I emphasize both algorithmic innovation and practical deployment; several first-author works are published in RSE, ISPRS, etc., with open-source implementations adopted by institutes such as the Sichuan Academy of Agricultural Sciences. Contact: tangkai@mail.bnu.edu.cn.

Research interests:
- Remote sensing change detection: high-resolution single/bi-temporal and medium-resolution time-series change
- Multi-source fusion: optical–SAR fusion and spatiotemporal reconstruction
- Agricultural remote sensing: crop mapping, sowing/harvest detection, yield estimation

<a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

# 🔥 News
- *2026.01* AnytimeFormer (SAR–optical asynchronous TS reconstruction) accepted by RSE
- *2026.01* Unsupervised disaster-affected area detection accepted by JRS
- *2024.12* ClearSCD semantic change detection published in ISPRS J P&RS
- *2024.09* BNU Graduate First-Class Scholarship
- *2025.01* BNU Academic Innovation Award

# 📝 Publications 
Representative first-author papers (* denotes me*):

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RSE 2026</div><img src='images/RSE_AnytimeFormer.png' alt="AnytimeFormer" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**AnytimeFormer: Fusing irregular and asynchronous SAR-optical time series to reconstruct reflectance at any given time.**  
*Remote Sensing of Environment*, 2026.

- Asynchronous SAR–optical TS reconstruction for arbitrary time queries.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISPRS J P&RS 2024</div><img src='images/ISPRS P&RS_ClearSCD.png' alt="ClearSCD" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**The ClearSCD model: Comprehensively leveraging semantics and change relationships for semantic change detection in high spatial resolution remote sensing imagery.**  
*ISPRS Journal of Photogrammetry and Remote Sensing*, 2024.

- Semantic change detection combining semantics and change relations.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JRS 2026</div><img src='images/JRS_Shield.png' alt="JRS change/anomaly" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Unsupervised detection of disaster-affected areas by combining the strengths of change detection and anomaly detection: target for on-orbit application.**  
*Journal of Remote Sensing*, 2026 (accepted).

- Unsupervised disaster damage detection for on-orbit application.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JAG 二审</div><img src='images/JAG_DreamCD.png' alt="DreamCD" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DreamCD: A change-label-free framework for change detection via a weakly conditional semantic diffusion model in high-resolution remote sensing imagery.**  
*International Journal of Applied Earth Observation and Geoinformation* (under 2nd round review).

- Label-free diffusion-based change detection.
</div>
</div>

- **Spatial downscaling of land surface temperature over heterogeneous regions using random forest regression considering spatial features.** *Remote Sensing*, 2021.  ![RS_SRF](images/RS_SRF.png)
- **Retrieving land surface temperature from Chinese FY-3D MERSI-2 data using an operational split window algorithm.** *IEEE J-STARS*, 2021.  ![JSTAR_LST](images/JSTAR_LST.png)
- **Destriping and Evaluating FY-3D MERSI-2 Data with the Moment Matching Method Based on Synchronous Reference Image.** *Journal of Applied Remote Sensing*, 2020.  ![Destrip_JARS](images/Destrip_JARS.png)
- In review/ready: real-time unsupervised crop harvest detection (IJAEOG, under review).

# 🧪 Projects
- NSFC Major Project “Remote sensing detection and instant diagnosis of surface anomalies” (2022.9–present): on-orbit instant change detection algorithms; results correspond to papers [2][3][9].
- National Key R&D Program “Intelligent recognition of cropland parcels and crop types in complex scenes” (2024.9–present): time-series reconstruction and harvest-date detection; results correspond to papers [1][8].
- Others: crop sowing date detection (Crop Journal, 2nd author); large-area crop mapping (ISPRS P&RS, revision, 2nd author); few-shot crop yield estimation (JAG, 3rd author).

# 🎖 Honors and Awards
- 2025.01 BNU Academic Innovation Award
- 2024.09 BNU Graduate First-Class Scholarship
- 2023.11 BNU Geography Graduate Academic Competition, First Prize
- 2022.05 Outstanding Graduate of Shandong Province
- 2021.10 National Graduate Scholarship
- 2021.09 Outstanding Sci-Tech Innovation Achievement (Shandong University of Science and Technology)
- 2021.09 Outstanding Graduate Student (Shandong University of Science and Technology)

# 📖 Educations
- 2022.09–2026.06 (Ph.D.): Beijing Normal University, Cartography & GIS, advised by Prof. Jin Chen
- 2019.09–2022.06 (M.Eng.): Shandong University of Science and Technology, Surveying & Mapping Engineering, advised by Prof. Hongchun Zhu
- 2015.09–2019.06 (B.Eng.): Shandong Agricultural University, Remote Sensing Science & Technology

# 🛠 Skills
- Programming: Python, IDL, Matlab, JavaScript; proficient with PyTorch
- Software: ArcGIS, ENVI, QGIS, Office
- Others: 65 original blogs on CSDN (410k+ visits, 3k+ saves)

# 💬 Teaching
- 2022.09–12 TA, “Remote Sensing and Uncertainty Analysis” (graduate course)
- 2020.09–12 TA, “Cartography and GIS” (undergraduate course)
