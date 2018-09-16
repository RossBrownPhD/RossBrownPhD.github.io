
---
layout: post
title: "Snarky Utilitarian or Abstruse: Comparing Movie Reviewers' Writing Style via NLP, nltk, cosine similarity"
date: 2018-09-16
---

Snarky, Utilitarian or Abstruse: Using Data Science to Compare Movie Reviewers' Writing Style

As a movie aficionado, I've spent far too much time reading movie reviews (or listening to them on the radio). I've developed perceptions of some movie reviewers' writing style. This data science project sought to verify these perceptions using a natural language processing technique that can quantify the similarity of text: cosine similarity of document vectors.

Below are pairs of movie reviewers whose work I'm familiar with, and an adjective that to my mind characterizes their writing style.

Anthony Lane and Rex Reed: Snarky
Dave Kehr and Jonathan Rosenbaum: Abstruse
Michael Wilmington and Richard Roeper: Utilitarian
Owen Gleiberman and David Edelstein: Urbane

I'm less familiar with some of the reviewers, so my perceptions may be off base, and the findings of this data science project may reflect misperceptions I have. 

I conducted pairwise comparisons of text from these reviewers on RottenTomatoes.com, comparing two reviewers hypothesized to have a similar writing style with a third reviewer hypothesized to have a writing style dissimilar to the other two. The measurements of text similarity range from zero to 1, with one reflecting identical vectors.

The results of the comparisons supported the pairings alluded to in the headline.

For example, text by Lane and Reed (snarky) was more similar (.89) than either was similar to utilitarian Roeper (.79 and .85, respectively).

Text by Kehr and Rosenbaum (abstruse) was more similar (.97) than either was similar to utilitarian Roeper (.88 and .90, respectively).

Findings from some comparisons aligned with my hypotheses, but the differences between text vectors weren't large enough to be meaningful. For example, Edelstein and Gleiberman (urbane) had a similarity score of .94, greater than either of them to snarky Reed (.89 and .92, respectively).

Overall, Kehr and Rosenbaum were more of apiece than any of the other pairs of reviewers with writing styles that were hypothesized to be similar. And Roeper's writing style was more frequently an outlier than any other reviewer's writing.

While this investigation had some interesting findings, I think there are more conceptually and methodologically robust ways to explore this area of inquiry.

Cut and paste the link below to check out the Jupyter notebook for other results and the code.

https://github.com/RossBrownPhD/Work_Samples_and_Resume/blob/master/08_NLP_nltk_and_vector_cosine_similarity_for_comparing_movie_reviewers_writing_style.ipynb

