---
title: 'Comparing Approximated Heat Stress Measures Across the United States'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yoonjung Ahn
  - Cascade Tuholske
  - Robbie M. Parks

# Author notes (optional)
author_notes:
  - Dr. Yoonjung Ahn led the writing, conducted the analysis, and created the visualizations.
  - Drs. Cascade Tuholske and Robbie Parks compiled the data and reviewed the manuscript. Drs. Tuholske and Parks contributed equally.

date: '2024-01-24 T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-24 T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['Paper']

# Publication name and optional abbreviated publication name.
publication: In *Geohealth*
#publication_short: In *ICW*
 
abstract: 
  Climate change is escalating the threat of heat stress to global public health, with the majority of humans today facing increasingly severe and prolonged heat waves. Accurate weather data reflecting the complexity of measuring heat stress is crucial for reducing the impact of extreme heat on health worldwide. Previous studies have employed Heat Index (HI) and Wet Bulb Globe Temperature (WBGT) metrics to understand extreme heat exposure, forming the basis for heat stress guidelines. However, systematic comparisons of meteorological and climate data sets used for these metrics and the related parameters, like air temperature, humidity, wind speed, and solar radiation crucial for human thermoregulation, are lacking. We compared three heat measures (HImax, WBGTBernard, and WBGTLiljegren) approximated from gridded weather data sets (ERA5‐Land, PRISM, Daymet) with ground‐based data, revealing strong agreement from HI and WBGTBernard (R2 0.76–0.95, RMSE 1.69–6.64°C). Discrepancies varied by Köppen‐Geiger climates (e.g., Adjusted R2 HImax 0.88–0.95, WBGTBernard 0.79–0.97, and WBGTLiljegren 0.80–0.96), and metrological input variables (Adjusted R2 Tmax 0.86–0.94, Tmin 0.91–0.94, Wind 0.33, Solarmax 0.38, Solaravg 0.38, relative humidity 0.51–0.74). Gridded data sets can offer reliable heat exposure assessment, but further research and local networks are vital to reduce measurement errors to fully enhance our understanding of how heat stress measures link to health outcomes.

# Summary. An optional shortened abstract.
summary:  
  - Extreme heat threatens human health. Rising intensity and duration of heat days expose more to hot environments. To understand how extreme heat affects human health, it is important to use accurate weather information and measures that reflect people's actual experience of the heat. Heat Index (HI) and Wet Bulb Globe Temperature (WBGT) are commonly used heat stress metrics that are widely used to set exposure guidelines and policies. However, there have been limited comparisons between daily heat measures and weather variables. In this study, we compared three heat measures (HI, WBGTBernard, and WBGTLiljegren) derived from three widely used gridded weather data sets (ERA5‐Land, PRISM, and Daymet) with ground‐based weather observations. The heat measures calculated from both the gridded weather data and the station data showed a reasonably strong agreement. However, the differences varied depending on the climate types. Gridded weather data sets can provide a reliable approach to assessing heat exposure and impacts based on meteorological variables to produce heat measures. However, further research and the establishment of local ground station networks are necessary to reduce measurement errors in exposure and improve accuracy. This will help us better understand the relationship between heat measures and their impact on health outcomes.

tags:
  - Extreme Heat

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2023GH000923'
url_code: 'https://github.com/YoonjungAhn/Daily_WBGT'
url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Ahn et al. (2024)**](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2023GH000923)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
