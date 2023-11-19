---
title: 'Learning with Safety Constraints: Sample Complexity of Reinforcement Learning for Constrained MDPs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Aria HasanzadeZonuzy
  - Archana Bura
  - Dileep Kalathil
  - Srinivas Shakkottai
  
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

#date: '' #2013-07-01T00:00:00Z
#doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-02-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

abstract: The predominant use of wireless access networks is for media streaming applications, but current networks treat all packets the same and can't determine which clients need service most urgently; with widespread software reconfigurability in networking devices, agile control policies can now be applied in access networks, requiring a system design that enables configuration, measures application performance impact (Quality of Experience), and adaptively selects new configurations, essentially a Markov Decision Process with unknown parameters; the goal is to develop QFlow, a platform to instantiate this loop and various control policies, using video streaming over YouTube as a use case, focusing on priority queueing and determining client assignments per queue each decision period; policies are developed using both model-based and model-free reinforcement learning, an auction-based system for priority service bidding, and a structured index-based policy, with experiments showing these policies on QFlow select the right clients for prioritization in high-load scenarios, outperforming known solutions with over 25% improvement in QoE and achieving a perfect QoE score of 5 over 85% of the time.

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
url_source: 'https://ojs.aaai.org/index.php/AAAI/article/view/16937'
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
