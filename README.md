# ouseful-data-notes

Notes and doodles on data and databases.

When we started writing the OU module *TM351 Data Management and Analysis* back in 2014, Jupyter notebooks were still IPython notebooks (and still relatively immature) and *pandas* was new but showing obvious signs of traction. So we took a punt on them both. The Docker container approach was still also very much in its infancy as we neared first presentation in 2016/17, so we went with Virtualbox virtual machines as a way of distributing module software.

Whilst we do try to refresh the practical notebook activities year on year, in part as a result of trying to keep things working as we update the packages in the virtual computing environment each year, the content of the module still largely remains the same as it was originally. The gaps that were there originally are still there — we don't cover the handling of streaming data, which I always thought would be a *nice to have*, and we don't really consider resource utilisation or optimisation (indexing, query optimisation), which I came to believe was at least a *should have* — and as things have moved on there are things that aren't that that probably now *should* be there — things like new file based storage formats such as parquet, or vector databases, which are now a key part of many generative-AI applications.

So as a way of keeping up-to-date with how data pipelines are evolving, and how data tooling is developing, I thought I'd start making some notes in a vaguely tutorial style.

Note that none of the contents of the repo will have been through an editor, and many of them will reflect my evolving understanding of the topics described. Which is to say, this will be as much a public learning diary as anything...
