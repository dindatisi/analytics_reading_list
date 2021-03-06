# Data Analytics Reading List
This is a selection of books and articles that I found useful. The contents might be related to statistics, data science, business, programming, or just analytical thinking in general. I will try to put summary or a brief background on each.

This list will be constantly updated and/or restructured as I find more reading materials.

## Books 
- [Thinking with data](https://learning.oreilly.com/library/view/thinking-with-data/9781491949757/). A very good book to get started on how to properly analyze data, from problem framing to the statistical techniques.
- [Storytelling with Data](https://www.amazon.com/Storytelling-Data-Visualization-Business-Professionals/dp/1119002257). Provide lots of basic principles for data visualization that can be broadly applied broadly to your slide decks, analysis reports, or dashboards.
- [Lean Analytics](https://www.amazon.com/Lean-Analytics-Better-Startup-Faster/dp/1449335675). I didn't read until the last chapter, but I found this book useful to teach me how to build a good & relevant metrics.
- [Black Swan: The Impact of Highly Improbable](https://www.amazon.com/Black-Swan-Improbable-Robustness-Fragility/dp/081297381X). An eye-opening book to remind us to look at beyond the data we see. I especially like the chicken analogy: A chicken is being fed by human every single day. After several days, it learned the pattern that whenever human comes, food will be served; not knowing that one day the chicken itself is the one who will be roasted and served as food. So lesson learned: what has happened in the past might not always be a good predictor of the future. 
- [Moneyball](https://www.amazon.com/Moneyball-Art-Winning-Unfair-Game/dp/0393324818). A real story on how analytics brought glory for a low budget baseball team. 
- [Naked Statistics](https://www.amazon.com/Naked-Statistics-Stripping-Dread-Data/dp/1480590185). This book is kinda similar with [The Signal and The Noise](https://www.amazon.com/Signal-Noise-Many-Predictions-Fail-but/dp/0143125087). But I like Naked Statistics better because it gives complete overview of basic statistics, the intuition and the common pitfalls, all in very light and brief explanation. 

## Short Articles 
- [Never start with a hypothesis](https://towardsdatascience.com/hypothesis-testing-decoded-for-movers-and-shakers-bfc2bc34da41). How many times have you encountered people who ask you to analyze data for the sake of "knowing it", without having an actual decision to make? This article gives guidelines on how to properly build a hypothesis before spending your time on extensive data analysis. It argues that unless you have default action (what you’d prefer to do if you stay ignorant), no fancy statistics is needed at all. The statistics inference is needed only to convince you to switch into alternative action.
- [Simpson’s Paradox: How to Prove Opposite Arguments with the Same Data](https://towardsdatascience.com/simpsons-paradox-how-to-prove-two-opposite-arguments-using-one-dataset-1c9c917f5ff9). If you haven't heard about Simpson's Paradox before, then this is a must read. Don't fall into the trap and make the wrong conclusion!
- [Mistakes, we’ve drawn a few](https://medium.economist.com/mistakes-weve-drawn-a-few-8cdd8a42d368). Good real examples on visualization mistakes and how to improve it from *The Economist*.
- [On Average - 99% Invisible](https://99percentinvisible.org/episode/on-average/). Using average as the standard measurement might not always be a good idea. What if nobody or nothing fits the average?
- [Geo Experiment](https://github.com/DusRUG/20191212-geo-experiments/blob/master/geo-experiments.pdf). This deck gives a light intro about how to measure incremental effect of a campaign with geo experiment & CausalImpact library in R. 
- [Gradient Boosting Decision Trees Algorithm Explained](https://towardsdatascience.com/machine-learning-part-18-boosting-algorithms-gradient-boosting-in-python-ef5ae6965be4). So I was reading a paper before I came across this article. I could not understand how gradient boosting tree works by reading the paper, but with that article I was able to understand the logic in a few minutes.
- [Bandit Test](https://cxl.com/blog/bandit-tests/) You've heard a lot about A/B test. Maybe you've also heard about Bayesian A/B test. But have you tried Bandit test? See when it's best to use bandit test in this article.

## Tutorials & Tips
- [Recommender System - Datacamp](https://www.datacamp.com/community/tutorials/recommender-systems-python). For those who want to learn to build a recommendation system in Python. This is one of the tutorials I followed when I first tried to build a reecommendation system for POI & Restaurants in London (I shared it on [this repo](https://github.com/dindatisi/next_to_visit)).
- [Jupyter Notebook Extension](https://towardsdatascience.com/jupyter-notebook-extensions-517fa69d2231). There are lots of hidden gems! I personally use Table of Contents (for navigation whenever my notebooks get very long) & Hide Code Input (because sometimes it's just quicker to present the notebook, and you might want to show the output cells only!). 
- [Cohort Analysis](http://www.gregreda.com/2015/08/23/cohort-analysis-with-python/). Cohort Analysis is very important when you want to measure retention & churn. This tutorial gives an example on how to do it in Python, along with the visualization.
- [Analytics Training - Mode Analytics](https://mode.com/sql-tutorial/sql-business-analytics-training/). It provies a set of cases to help you practice solving analytical problems, from thinkin through the possible scenario, to actually checking the data with SQL queries & charts.

## Slightly Longer Reads (Papers, mostly)
- [Online Experimentation at Microsoft](https://ai.stanford.edu/~ronnyk/ExPThinkWeek2009Public.pdf). Stories & lesson learned from past experiments at Microsoft.
- [A Comparison of Approaches to Advertising Measurement](https://www.kellogg.northwestern.edu/faculty/gordon_b/files/fb_comparison.pdf). For those interested in running & evaluating campaigns on Facebook ads, this paper provides a comparison for different approaches to measure the impact of the experiment. It explains why the measurement is not straightforward and what factors need to be considered. 


