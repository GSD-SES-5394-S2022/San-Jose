# San Jose

## Abstract

A thriving, populous city as San Jose, California, is the ideal environment for exploring transportation implications from working from home trends given the strong presence of the tech sector. Although this industry had pioneered in these practices many years before, it is undeniable how the Covid-19 pandemic accelerated a transition to remote activities when possible, needed, or desired. The analysis expects to forecast not only reductions in Vehicle Miles Traveled (VMT) and/or ridership, but also to see some uneven distribution of travel changes because of how jobs and their associated industries are concentrated across the territory. Additionally, results and implications will be also mindful of inequalities of other kinds, regardless of the location: namely low income, no vehicle ownership, and unemployment / inactivity at the household level.

## The MSA

San Jose, located in the heart of Santa Clara Valley in California, is the most populous city in Northern California and the third most populous city in the state (according to 2020 Census, 1,013,240 inhabitants, and a decennial growth rate of 7.1%). It is also the largest city by area in Northern California, and the major city (with half of its inhabitants) of its MSA, the San Jose-Sunnyvale-Santa Clara Metropolitan Statistical Area (MSA).

The metropolitan region is ranked second for the most expensive rent by the National Low Income Housing Coalition. The median home price is $1.3 million and buyers’ income is at least $203,000 for affordability. This is strongly related to San Jose’s location in Silicon Valley. The high growth in the tech sector in the past decades, driven by large employers such as Apple and Google, contributed to a rise in the average annual salary to $83,960 (as of 2021, this was 1.57x the national average). The tech sector also provided a quick recovery from the recession brought by the pandemic.

## Methodology

Using census tracts, the number of employees (labor supply) and jobs (labor demand) were considered according to broad categories of industries. Both were added up since LEHD OnTheMap data suggested the share of employees working at their same tract was negligible, so theoretically possible overlaps are disregarded in practice.

'Service jobs' were considered, as opposed to 'Retail jobs' or 'Basic jobs', as suitable for working from home. This definition is a simplification, since belonging to an industry does not imply by itself the type of task that is performed (which is what actually would define suitability for remoteness). The assumption is that in quantitative terms, the effects are canceled (the service jobs that are not suitable for WFH compensate basic and retail jobs that are) and that spatial distribution might experience some noise because of this, however.

Under a hypothesis of upcoming paradigms that imply working from home on a twice-a-week basis, this would mean employees do not commute to their jobs 40% of the week. Considering the object of this travel forecasting exercise is an average weekday, this is equivalent to reducing 40% of the workforce + positions in the industry (assuming WFH choice is uniform along the week, e.g., ignoring any biases towards Fridays). It must be acknowledged, however, that this reduction is not only related to the pandemic's aftermath: probably some of these workers were remote once a week, for example, meaning that some percentage points of 40% already worked from home. An additional implication is that for commuting purposes, those jobs and employees disappear, but projected behavior for these workers will not be equivalent to that of an unemployed, and might imply other kinds of travel. These workers are not completely deleted, but just unobservable in terms of commuting.

## Repository Structure

The repository consists of