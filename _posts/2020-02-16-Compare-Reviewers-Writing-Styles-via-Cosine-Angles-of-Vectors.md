---
layout: post
title: "Comparing movie reviewers' writing styles via NLP, nltk, cosine similarity"
date: 2020-02-16
---

Snarky, Utilitarian or Abstruse: Using Data Science to Compare Movie Reviewers' Writing Styles

This project uses Natural Language Tool-Kit (NLTK) for text preprocessing, then assesses the similarity of document pairs using the cosine of the angle between two vectors.

As a movie aficionado, I've spent far too much time reading movie reviews (or listening to them on the radio). I've developed perceptions of some movie reviewers' writing styles. This data science project sought to verify these perceptions using a natural language processing technique that can quantify the similarity of text: cosine similarity of document vectors.

Below are pairs of movie reviewers whose work I'm familiar with, and an adjective that to my mind characterizes their writing style.

Anthony Lane and Rex Reed: Snarky

Dave Kehr and Jonathan Rosenbaum: Abstruse

Michael Wilmington and Richard Roeper: Utilitarian

Owen Gleiberman and David Edelstein: Urbane

I'm less familiar with some of the reviewers, so my perceptions may be off base, and the findings of this data science project may reflect misperceptions I have. 

I conducted pairwise comparisons of text from these reviewers on RottenTomatoes.com, comparing two reviewers hypothesized to have a similar writing style with a third reviewer hypothesized to have a writing style dissimilar to the other two. The measurements of text similarity range from zero to 1, with 1 reflecting identical vectors.

The results of the comparisons supported the pairings alluded to in the headline.

For example, text by Lane and Reed (snarky) was more similar (.89) than either was similar to utilitarian Roeper (.79 and .85, respectively).

Text by Kehr and Rosenbaum (abstruse) was more similar (.97) than either was similar to utilitarian Roeper (.88 and .90, respectively).

Findings from some comparisons aligned with my hypotheses, but the differences between text vectors weren't large enough to be meaningful. For example, Edelstein and Gleiberman (urbane) had a similarity score of .94, greater than either of them to snarky Reed (.89 and .92, respectively).

Overall, Kehr and Rosenbaum were more of apiece than any of the other pairs of reviewers with writing styles that were hypothesized to be similar. And Roeper's writing style was more frequently an outlier than any other reviewer's writing.

To see the code, the full results, and a technical discussion of the relative benefits of cosine similarity to other methods for creating vectors from text, copy and paste the link below:

Copy and paste the link below to check out the Jupyter notebook for other results and the code.

http://bit.ly/2OZTLNb

