# email-network-analysis
Create a shiny app to analyze the communication network of a large organization

In this project, I visualize and analyze the email network of a large organization
(over 1000 employees and 25,000 emails exchanged). Specifically, I will:
1. Visualize n connections in the email network, with n as your number input
2. Display a summary how many emails are sent and received by each person
3. Display up to 2-hop neighbors of the top 10 senders and receivers
4. Explore degree centrality and betweenness centrality
5. Display a summary how many emails are exchange between any two departments

A question for further exploration is how to display 2-hop neighbors for the most popular nodes.
They'll appear as a hairball, so I'm thinking about coloring the 1-hop and 2-hop differently or
only display 2-hop neighbors within certain departments.

Packages: shiny, networkD3, igraph
