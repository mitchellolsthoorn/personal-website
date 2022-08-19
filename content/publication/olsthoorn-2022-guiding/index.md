---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Guiding Automated Test Case Generation for Transaction-Reverting Statements in Smart Contracts"
authors:
  - Mitchell Olsthoorn
  - Arie van Deursen
  - Annibale Panichella

# The date it was published
date: 2022-07-01
doi: ""

# Schedule page publish date (NOT publication's date).
# Use the paper notification date
publishDate: 2022-07-01

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 38th IEEE International Conference on Software Maintenance and Evolution"
publication_short: "ICSME'22"

abstract: "Transaction-reverting statements are key constructs within Solidity that are extensively used for authority and validity checks. Current state-of-the-art search-based testing and fuzzing approaches do not explicitly handle these statements and therefore can not effectively detect security vulnerabilities. In this paper, we argue that it is critical to directly handle and test these statements to assess that they correctly protect the contracts against invalid requests. To this aim, we propose a new approach that improves the search guidance for these transaction-reverting statements based on interprocedural control dependency analysis, in addition to the traditional coverage criteria. We assess the benefits of our approach by performing an empirical study on 100 smart contracts w.r.t. transaction-reverting statement coverage and vulnerability detection capability. Our results show that the proposed approach can improve the performance of DynaMOSA, the state-of-the-art algorithm for test case generation. On average, we improve transaction-reverting statement coverage by 14 % (up to 35 %), line coverage by 8 % (up to 32 %), and vulnerability-detection capability by 17 % (up to 50 %)."

# Summary. An optional shortened abstract.
summary: ""

tags:
  - search-based software testing
  - test case generation
  - fuzzing
  - software testing
  - smart contracts
categories: []
featured: false
add_badge: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://research.tudelft.nl/en/publications/guiding-automated-test-case-generation-for-transaction-reverting-
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [ubri]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
