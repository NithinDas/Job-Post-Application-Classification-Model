# Job-Post-Application-Classification-Model

Imagine a user visiting Job Portal, and performing a job search. From the set of displayed results, user clicks on certain ones that she is
interested in, and after checking job descriptions, she further clicks on apply button therein to land in to an application page. The apply rate is defined as the fraction of applies (after visiting job description pages), and the goal is to predict this metric using the dataset described in the following section.

1) title proximity tf idf: Measures the closeness of query and job title.
2) description proximity tf idf: Measures the closeness of query and job description.
3) main query tf idf: A score related to user query closeness to job title and job description.
4) query jl score: Measures the popularity of query and job listing pair.
5) query title score: Measures the popularity of query and job title pair.
6) city match: Indicates if the job listing matches to user (or, user-specified) location.
7) job age days: Indicates the age of job listing posted.
8) apply: Indicates if the user has applied for this job listing.
9) search date pacif ic: Date of the activity.
10) u id: ID of user (for privacy reasons ID is anonymized).
11) mgoc id: Class ID of the job title clicked.

Predicting the 'apply' rate based on the features.
