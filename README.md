# Open Domain Question Answering System
In this project, we implemented a robust open domain question Answering system. 

When a user lodges a query into the system, the system scrapes Top 10 webpages from Google Search API.
Then various document shortening algorithms are experimented with to summarize the contents of the webpages so that the answers are retained. Further, BigBird Question Answering Model is used to extract the precise answers from the shortened context and returned.

This project works best for Wh- and yes/no questions and can partially answer the indirect questions.

