# email-network-analysis
Create a shiny app to analyze the communication network of a large organization

In this project, I visualize and analyze the email network of a large organization
(over 1000 employees and 25,000 emails exchanged). Specifically, I will:
1. Visualize n connections in the email network, with n as your number input
2. Display a summary how many emails are sent and received by each person
3. Display up to 2-hop neighbors of the top 10 senders and receivers

You can upload your own datasets and apply the same analysis. The first one is the
nodes dataset, with the two columns as ID and Group of the nodes. The second
one is the links dataset, with the two columns as source and target.

Packages: shiny, networkD3, igraph
