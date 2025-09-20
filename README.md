# Comparative Rating System

HKU BEng(CS) final year project: A rating system using only comparisons

## Resources

### Existing implementations

|Implementation|Description|Features|Paper|
|--------------|-----------|--------|-----|
|[All Our Ideas](https://all-our-ideas.citizens.is/domain/1)|Survey creator|Raters can add new items, unequal votes per rater, rate by Thurstone-Mosteller|[Link](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0123483)|
|[LMArena](https://lmarena.ai/)|AI model rating website|Website can add new models, unequal votes per rater, rate by Bradley-Terry|[Link](https://arxiv.org/abs/2403.04132)|
|OpinionX ([Pair Rank](https://knowledge.opinionx.co/en/articles/5866366-pair-rank-scoring-examples-and-other-faqs), [Best-Worst](https://knowledge.opinionx.co/en/articles/9145942-best-worst-rank-free-maxdiff-analysis-surveys))|Survey creator|Calculates sample size required, rate by win rate||
|[PollUnit](https://pollunit.com/en/posts/170/pairwise-comparison)|Survey creator|Rate by Elo rating||
|[What is the Best Thing?](https://www.youtube.com/watch?v=ALy6e7GbDRQ)|Survey website|Unequal votes per rater, rate by win rate||

### Inference algorithms

|Algorithm|Features|
|---------|--------|
|[Bradley-Terry](https://web.stanford.edu/class/archive/stats/stats200/stats200.1172/Lecture24.pdf)|Fit a statistical model of pairwise comparisons|
|[Plackett-Luce](https://hturner.github.io/PlackettLuce/articles/Overview.html)|Fit a statistical model of multiple comparisons|

### Datasets

- [Netflix Prize dataset](https://discord.com/channels/1384526621142290492/1384526621142290495/1415185464008245248): a large 5-star Likert scale dataset

### Books

- Kahneman, D., Sibony, O., &  Sunstein, C. R. (2021). [*Noise: A flaw in human judgment.*](https://ia804606.us.archive.org/11/items/ar_20211024/BOOKS.YOSSR.COM-Noise-A-Flaw-in-Human-Judgment.pdf) William Collins.
Chapters 14, 15, and 23 explain how rating scales create unwanted variance ("noise") and how comparative judgment can reduce it.
