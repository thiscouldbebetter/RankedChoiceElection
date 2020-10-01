RankedChoiceElection
====================

The JavaScript code in this repository implements a ranked-choice election system.

To see it in action, open the file Source/RankedChoiceElection.html in a web browser that runs JavaScript.

In a ranked-choice election, each voter specifies a list of candidates in descending order of preference. The list could include every single candidate, or a particular subset of the candidates, or even just a single candidate. Then each voter's first choice is tabulated. The candidate or candidates with the fewest votes are eliminated from the election. Then the votes are tabulated again, with any votes for eliminated candidates replaced with those voter's next preferred candidate. The process repeats until there is either only one candidate remaining, or at least all remaining candidates have the same number of votes.

In the case where each voter specifies a single candidate, it acts just like a traditional, "first-past-the-post" election.  But allowing the voters to specify a list of preferred candidates rather than a single candidate addresses some of the shortcomings of traditional voting, such as a "splitting the vote" scenario, when there are two or more candidates with similar platforms, whose supporters, when combined, make up a plurality of the electorate, but who lose to a third candidate who is actually less popular than either of the first two would have been if they had been the only candidate representing their bloc.

<image src="Screenshot.png" />
