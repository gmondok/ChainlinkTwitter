# ChainlinkTwitter
Uses the twitter-cl-ea on market.link to post a Twitter status from a smart contract

Contract owner can call tweet(string memory twt) which will tweet the supplied string to the Twitter account associated with the jobID.
The oracle node define's the Twitter API key info via env variables as outlined in the market.link page for the external adapter.
https://market.link/adapters/9ebb251e-1d7c-433d-9835-d771996f5b9c

The tweet's status code is returned to the publicly viewable statusCode variable.
