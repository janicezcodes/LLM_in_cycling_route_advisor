# LLM_in_Cycling_Route_Advisor
Application of LLM in building a conversational web app that recommends the most ideal cycling route for cyclists in Singapore.

A conversational bicycle routing web application was built to leverage the power and interactive nature of Generative AI. Compared with existing bike routing tools like Google Map and BikeMap, the solution provides more personalized recommendations on the most ideal bike-friendly routes while engaging contents from the cyclist community. More specifically, it is able to recommend cycling routes based on user requests such as "I want a route from _point A_ to _point B_ along the river", "I prefer a route with least elevation", "please recommend a quiet route" and so on. 

<br>
<img width="1136" alt="image" src="https://github.com/janicezcodes/LLM_in_cycling_route_advisor/assets/71380413/28af12f4-f550-4aaf-aef5-c8c1a27f0100">
<br><br> **Components of the solution**:
<br> - Input and output web interface was built using Flask.
<br> - An open-source LLM platform, Cohere, was used to interpret user requests and output the route summary. Retrieval-augmented generation (RAG) was performed to enhance the accuracy and reliability of Cohere model. 
<br> - To make the route recommendation more informative, a variety of data sources were utilised in enriching the recommendation. For example, information on bike parking racks was obtained from data.gov.sg and then visualised on the map.  
<br> - BRouter-web was the underlying routing algorithm for this solution. 
