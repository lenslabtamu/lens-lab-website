---
title: 'Learning to Cache and Caching to Learn: Regret Analysis of Caching Algorithms'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Archana Bura
  - Desik Rengarajan
  - Dileep Kalathil
  - Srinivas Shakkottai
  - Jean-Francois Chamberland
  
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

#date: '' #2013-07-01T00:00:00Z
#doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-08-26T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

abstract: Crucial performance metrics of a caching algorithm include its ability to quickly and accurately learn a popularity distribution of requests. However, a majority of work on analytical performance analysis focuses on hit probability after an asymptotically large time has elapsed. We consider an online learning viewpoint, and characterize the “regret” in terms of the finite time difference between the hits achieved by a candidate caching algorithm with respect to a genie-aided scheme that places the most popular items in the cache. We first consider the Full Observation regime wherein all requests are seen by the cache. We show that the Least Frequently Used (LFU) algorithm is able to achieve order optimal regret, which is matched by an efficient counting algorithm design that we call LFU-Lite. We then consider the Partial Observation regime wherein only requests for items currently cached are seen by the cache, making it similar to an online learning problem related to the multi-armed bandit problem. We show how approaching this “caching bandit” using traditional approaches yields either high complexity or regret, but a simple algorithm design that exploits the structure of the distribution can ensure order optimal regret. We conclude by illustrating our insights using numerical simulations.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
url_source: 'https://ieeexplore.ieee.org/document/9523607'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
