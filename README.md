# Facebook-Engagement-Predictor
Facebook is one of the largest social media platforms on the internet, where users can interact with each other and produce content. Content can come in the form of text posts, images, videos, or other forms of media. 

As the popularity of social media continues to grow at an exponential rate, so does the need for businesses and influencers to take advantage of the various platforms available to grow their brand. A large amount of reach on social media yields a large fanbase, which in turn increases the brand influence. Brands and businesses can achieve this by finding ways to improve their reach through increasing engagements.


‘Engagements’ is the system used by the platform to gauge traction gained by posts. The total number of engagements is the total number of likes, comments, and shares. The more engagements a post gains, the more likely it is to be viewed by other accounts, and the larger the reach gained by the user that posted it. 

The easiest and most effective way to gauge the popularity of a post is by looking at the number of ‘likes’ it receives. Therefore, a brand or business that finds a systematic method to improve the number of likes per post, will be able to increase its reach, popularity, and value much more than a brand that doesn’t take advantage of the system.  

Social media growth experts have theorized that there are multiple ways to increase the popularity of a page, by increasing the number of engagements its posts receive.
Some of the variables that can be used include: The rate at which a page produces content/posts, the type of the post, the time of the day at which the post is put out, and the number of comments. Evidently, we can theorize that a page/user with an already large following is more likely to gain traction on their posts compared to a smaller account. 

Due to the sheer variety of variables available that can be manipulated to improve engagements, it should be possible for a business to formulate an algorithm that predicts the number of engagements or likes that a post receives.  We will attempt to create such a model, as we believe that a prediction algorithm is an excellent way to increase the popularity of an account, and consequently, the reach of the brand/business that runs it.



The method used to produce this prediction model will be KNN-regression, as all of the variables suggested are quantitative. We will be able to use a mixture of pre-posting variables as well as variables determined after the post is produced, to predict the number of likes that it receives.

To produce this model, we will use a dataset obtained from the machine learning database https://archive.ics.uci.edu/ml/datasets/Facebook+metrics.  The dataset contains a random selection of Facebook posts from a multitude of accounts. The latter vary in lifetime likes and visibility. Furthermore, the posts are a selection of images, status updates, videos, and links.
