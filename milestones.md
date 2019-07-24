The main milestones of a project such as scikit-learn are the stable releases.
Depending on the activity on the project, the span between two stable versions
is usually between 6 months and 1 year. A feature can be considered *delivered*
once it is merged into scikit-learn's master branch: it means it will be part
of the next stable release.

General maintenance
-------------------

We consider number of solved issues and fixed bugs, and number of reviewed and
merged pull requests, as well as the trend of open issue and pull requests.
Even though the amount of time required to review a pull request varies from a
few minutes to many months, depending on the activity of the contributor and
the complexity of the task, we hope this metric provides some insight into
project health.

We expect to have around 10 smaller pull requests reviewed per month, and at least
10 complex pull requests (such as major new features or changes to the API) reviewed and merged in the span of 12 months. We
also expect simple and/or critical bugs to be fixed within a few weeks, i.e.
before the next bug-fix release.

Improvements to GBDTs
---------------------

Regarding the Gradient Boosting Decision Trees (GBDT) improvements, we are
planning on the following timeline:

1 month: Start work on missing values and documentation.
3 months: Missing values support is implemented, and ready for reviews.
Documentation for GBDTs is written and merged into the master branch.
6 months: Support for missing values is merged into the master branch. Start
work on categorical variables.
9 months: Support for categorical variables is implemented and ready for
reviews.
12 months: Support for categorical variables is reviewed and merged into the
master branch. A stable release should follow soon.

We expect support for sample weights and class weights to be merged during that
year. Similarly, we expect to improve scalability on multi-core systems iteratively throughout the term of the grant.

Note that the person submitting a pull-request cannot also review their own PR:
this means that the completion of these timelines strongly depend on the
availability of other core-developers.

We expect these new features to increase usage of the HistGradientBoosting
models, as can be measured by code search on Github. Currently a search for
Jupyter Notebook returns about 50 hits, we expect this to rise to over 200.

Faster parameter searches
-------------------------

Regarding the support for parameter searches without redundant computation, we
are planning on the following timeline:

1 month: Start
6 months: Discussion is strongly engaged among the core developers, and some
first prototype(s) may be implemented.
9 months: Pros and cons of each approach are clearly defined and understood.
12 months: Consensus is reached on the implementation path. A release of the
implementation would be a stretch goal.

