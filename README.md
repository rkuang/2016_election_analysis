# 2016 Election Analysis

## Background

The presidential election in 2012 did not come as a surprise. Some correctly predicted the outcome of the election correctly including [Nate Silver](https://en.wikipedia.org/wiki/Nate_Silver), and [many speculated his approach](https://www.theguardian.com/science/grrlscientist/2012/nov/08/nate-sliver-predict-us-election).

Despite the success in 2012, the 2016 presidential election came as a [big surprise](https://fivethirtyeight.com/features/the-polls-missed-trump-we-asked-pollsters-why/) to many, and it was a clear example that even the current state-of-the-art technology can surprise us.

Predicting voter behavior is complicated for many reasons despite the tremendous effort in collecting, analyzing, and understanding many available datasets. 

It's hard to predict behavior because it can change at any time. Up until election day, candidates can do many things that change how the public views him or her. All of that uncertainty makes election forecasting a difficult problem.

### 2012 Election vs 2016 Election

In 2012, Nate Silver of FiveThirtyEight successfully predicted the presidential election to great accuracy. While others used a weighted average on pollsters, they failed to note that pollsters can suffer from bias. If a pollster was in favor of one candidate winning, they're more likely to give better and better odds to that candidate as time progresses. Nate Silver recognized this and was able to formulate a way to weigh this bias as well. This was essentially a double layered approach to weighted averages that reduced error even further.

In 2016, many individual polls were wrong and predicted many states incorrectly. National polls were wrong in the same direction, exascerbating the errors. Overall, the errors spread unevenly, and the polls underestimated Trump's chance of victory in many crucial states. I believe there needs to be a better way of analyzing which polling results are more trustworthy, thereby allowing data scientists to weigh each poll more accurately and reduce the amount of error.
