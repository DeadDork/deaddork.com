---
layout:    post
title:     "How to use drafts"
date:      2013-12-20 17:26:51
published: false
categories: jekyll update
---

Markdown is a WYMIWYG language, and GitHub-flavored Markdown is not fully documented. As such, I frequently find myself pushing a Markdown file, seeing the compiled horror I have unwittingly wrought to an innocent README.mkd, and then entering a furious cycle of pushing revisions until I'm looking at something a little less horrible.

Well, guess what: I'm not doing that with my blog.

From here on out, I will be using Jekyll's `_drafts` feature.

Detailed instructions [here](http://jekyllrb.com/docs/drafts/), but simply put:

1.	Write a draft in `_drafts` (be sure to name the Markdown file without the date prefix).
2.	Serve the site locally:

	```bash
	jekyll serve --drafts --watch
	```
3.	Revise until the damned thing doesn't make you want to swallow your own tongue.
4.	Copy the draft to your `_Posts` directory, but be sure to prepend the file name with the date correctly.

(And I guess end the local Jekyll server & push the post?)
