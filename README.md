Network Traffic Analysis

Overview
This project involves analyzing network traffic data from sFlow logs (.csv format) using Python. It focuses on identifying key network participants, protocol distribution, and visualizing communication patterns between hosts.

Key Features
1. Top Talkers & Listeners: Identifies the top 5 source and destination IP addresses, including their organization and country via WHOIS lookup.

2. Protocol Analysis: Calculates the distribution of Transport Layer protocols (TCP, UDP, etc.) and Application Layer services (HTTP, HTTPS, etc.).

3. Traffic Estimation: Estimates total network traffic volume in MB based on packet size and sampling rates.

4. Data Visualization:

  Heatmaps: To show communication intensity between IP pairs.

  Network Graphs: To visualize the network topology and traffic hubs.

  Chord Diagrams: To display bidirectional traffic relationships.


Technical Stack
1. Language: Python 3

2. ibraries: pandas, matplotlib, seaborn, networkx, plotly, ipwhois.


Key Findings
1. Traffic Concentration: A small number of IP addresses (hubs) account for the majority of the traffic.

2. Protocol Dominance: TCP is the primary transport protocol, with HTTPS (Port 443) being the most used application service.


Usage
1. Place the dataset (Data_2.csv) in the project directory.

2. Run the Jupyter Notebook lab4.ipynb to execute the analysis and generate visualizations.
