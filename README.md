# major-donor-prediction
Using data on donor interactions with a large charity, can we predict when a minor donor is likely to become a major donor for targeted donation requests?

Our model for predicting which existing donors from 2014-17 would become major donors in 2018 acheived 0.93 accuracy with 0.70 recall. We prioritized recall over precision since we want to capture as many major donors as possible, while false positives are not very detrimental.

We were presented with data on nearly 300,000 individual donations received by the charitable organization between 2014-18 and given free range to analyze the data for whatever insights we could find. In our initial inspection we found that a great majority of the total donation value came from a very small number of major donors, defined as those who have given a single donation of $1000 or more. We expected that the most valuable insight in the data would be to predict when a minor donor is likely to become a major donor. Then those people could be actively targeted with major donation requests.



The donation data we worked on cannot be included in the repository due to confidentiality. This work was done for the Data for Good Datathon held on Oct. 27, 2018 at the SAS Institute, Toronto, in collaboration with Kevin Marshall, Hoan Bui Dong, and Laks Vajjhala of Capco.
