---
# ==========================================================================
#  NEW GUIDE. Fill this in, then delete any line you do not need.
# ==========================================================================
title: "Put the headline here"
metaTitle: "Put the Google title here | Simply Cozy Homes"
description: "One or two sentences for Google. Around 150 characters."
date: {{ now.Format "2006-01-02" }}
weight: 10                      # smaller number = higher up the guides page
category: "kitchen"             # a key from hugo.toml blogCategories
badge: "Kitchen"                # short label shown on the card
readTime: "5 min read"
lede: "One line under the headline at the top of the article."
intro: "The opening paragraph of the article."
cardBlurb: "The short line shown on the guides page card."
image: "images/post-1.jpg"
imageAlt: "Describe the photo for screen readers"
pick:
  text: "Why this product suits the topic."
  url: "#"                      # PASTE YOUR PRODUCT LINK HERE
  label: "View the pick"
---

## First question as a heading

Answer it in the first sentence.

## Second question as a heading

More of your writing here.

{{</* pick eyebrow="Featured pick" name="PRODUCT NAME" url="#" label="View the pick" */>}}
A sentence about the product.
{{</* /pick */>}}
