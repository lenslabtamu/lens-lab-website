---
title: 'DOPE: Doubly Optimistic and Pessimistic Exploration for Safe Reinforcement Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Archana Bura
  - Aria HasanzadeZonuzy
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
publishDate: '2022-10-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

abstract: Safe reinforcement learning is extremely challenging--not only must the agent explore an unknown environment, it must do so while ensuring no safety constraint violations. We formulate this safe reinforcement learning (RL) problem using the framework of a finite-horizon Constrained Markov Decision Process (CMDP) with an unknown transition probability function, where we model the safety requirements as constraints on the expected cumulative costs that must be satisfied during all episodes of learning.We propose a model-based safe RL algorithm that we call Doubly Optimistic and Pessimistic Exploration (DOPE), and show that it achieves an objective regret \( \sim O(|S|\sqrt{|A|K}) \) without violating the safety constraints during learning, where \( |S| \) is the number of states, \( |A| \) is the number of actions, and \( K \) is the number of learning episodes. Our key idea is to combine a reward bonus for exploration (optimism) with a conservative constraint (pessimism), in addition to the standard optimistic model-based exploration. DOPE is not only able to improve the objective regret bound, but also shows a significant empirical performance improvement as compared to earlier optimism-pessimism approaches.

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
url_source: 'https://papers.nips.cc/paper/2022/hash/076a93fd42aa85f5ccee921a01d77dd5-Abstract-Conference.html'
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
