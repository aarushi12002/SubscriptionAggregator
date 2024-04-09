# SubscriptionAggregator
Problem: you subscribe to too many newsletters, RSS feeds, but that can get lost in your emails. One could categorize and add them to a folder but one still needs to go through each one of them which is ineffective. A collective one page summary of all topics from different newsletters can help you digest information in a more efficient manner. Additionally, the customer should have the ability to filter the results based on topics of interests.

Vision:

- Effective and concise information gathering and results for diverse topics, weekly digest based on user context and interests. The user context can be learnt from user inputs and profiles.

Components:

- Cron job to collect news/blogs daily, weekly, monthly
- Aggregator: aggregates feed from different newsletters
- Ability to add new RSS feeds/newsletters
- Context aware information gathering and display: Returns relevant results based on user session context, inputs, profile, interests
- Tagging the data - this is to identify the topics so the user can filter on those
- Summarizer: summarizes all the feeds with read more links
