# Introduction
The Prosper dataset contains all the transaction and member data since its inception in November 2005. This is a considerable volume of information that encloses approximately (by December2008) 6
Million bids, 900,000 members, 4,000 groups and350,000 listings. In order to facilitate the analysis of the data, the dataset was filtered to contain all the loans created in calendar year 2007 and all the
listings created in calendar year 2007, the bids created for these listings, the subset of members that created these listings and bids, and finally, the groups these members are affiliated with.
The following table shows the approx. records available based on the status out of 9479 observations. However, our interest is to predict whether the loan would be timely paid or not. So we will be replacing
fully Paid status to “Good”, indicating borrower is a good borrower and for the rest will be replacing to “Bad”, indicating a bad borrower.
