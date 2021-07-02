# TwitterBotNBAA
Twitter bot extension for N.B.A.A.

Checks last 20 mentions (tweets directed at @_NBAA_) and if tweet has proper formatting and has not been liked,
the bot replies to the tweet with its prediction and then likes the tweet.

format of tweet : "@_NBAA_ MIA vs. LAL"

To run this for an extended period of time, add a while loop with a true condition. Add a pause function of some kind if you want to limit API calls but currently not a concern for me

