# CSDS-234-Tax-Haven-Project


This project investigates the use of offshore financial entities by modeling the Panama Papers dataset (from the ICIJ Offshore Leaks) as a temporal graph using Neo4j. The graph consists of nodes representing people (Officers), companies (Entities), and facilitators (Intermediaries), along with relationships like ownership, management, and registration.

Using this graph, we develop a series of Cypher queries to detect potential tax haven patterns. We focus on identifying:

Foreign ownership concentrations (a core tax haven trait)

Network clusters of high-volume agents

Temporal trends in incorporation and shutdowns

Jurisdictional hotspots

Suspiciously reactivated companies

The project demonstrates how graph databases enable pattern recognition across complex global financial networks. By querying the graph structure, we extract insights into how shell companies are organized, how facilitators operate across jurisdictions, and how activity changes over time.
