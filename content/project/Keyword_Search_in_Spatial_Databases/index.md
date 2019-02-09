+++
title = "Keyword Search in Spatial Databases"
date = 2019-02-08T14:28:04-08:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["research","academic"]

# Project summary to display on homepage.
summary = "Course work for Research Methods in Computing <br>"

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Links (optional).
url_pdf = "https://github.com/PrasannaNatarajan/lit_review/blob/master/Atish_Prasanna_Vedant_mCK.pdf"
url_code = ""
url_dataset = ""
url_slides = "https://github.com/PrasannaNatarajan/lit_review/blob/master/Atish_Prasanna_Vedant_mCk.pptx"
url_video = ""
url_poster = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

### Introduction

In a database of spatial objects, every tuple is associated with certain information represented by keywords. This paper introduces a new type of spatial keyword query, known as the m-closest keywords (mCK) query. The aim of the mCK query is to find tuples which are located in the closest spatial proximity that align with the user-entered keywords. In order to efficiently process mCK queries, a new index is introduced, known as the bR*-tree, which is an extension of the R * tree. Following this, a priori based search approaches are used to decrease the total search space. There is extensive research being conducted on various forms of spatial queries, above and beyond the general one- nearest neighbour queries, range queries, and spatial joins. Keyword based queries have received significant attention in the research community. This paper presents a novel query, the m-closest keywords (mCK) query. An mCK query returns the closest tuples in any space which match certain keywords, given a set of m keywords as input. The main focus of the paper is to apply this mCK query in searching by document. A given tuple can be associated with as many as m keywords, hence the total number of responses that can be possibly returned from a mCK query is at most m. A problem which arises from this is that the value of m might become very large while searching by document, in which case the naive mCK query processing would become very computationally as well as temporally intensive, as the number of possibilities to examine all possible set of m tuples of objects matching the keywords would be needed. This process is extremely expensive and hence is not a good approach. This paper proposes to improve upon this by using a new index, known as the bR*- tree, for processing queries. The bR*- tree extends the R*-tree to efficiently summarize keywords and their spatial information. Following this, a-priori based search strategies are used to significantly reduce the search space. For application of said search strategies, some constraints are required to prune the dataset. The paper defines two such monotone constraints, the distance mutex and the keyword mutex. Finally, using all the above, the algorithm is tested and is found to be effective in reducing mCK query response time, but also provides scalability with regards to the number of keywords in the query. 



The full paper can be found [here](https://github.com/PrasannaNatarajan/lit_review/blob/master/Atish_Prasanna_Vedant_mCK.pdf).