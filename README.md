<h3>Network Topology Analysis</h3>
A network topology consists of many nodes (or hosts) and edges (connections) that link each of the nodes. In communication systems, there are typically many routes that we can take to get from Point A to Point B. 
<br>
<br>For example, if you are on your home wifi (Point A) and you request a webpage from Google.com (Point B), then your request will be relayed through many hosts along the route. Each time you make the request, a slightly different path may be used based on how the network is optimized, timeouts, failed nodes, etc. 
<br>
<br>For communication providers, these failed nodes create a problem. Isolating and resolving the issue is critical, since a failed node reduces performance, may cause downtime, cost money if a truck or person needs to manual troubleshoot a node, etc.
<br>
<br>Even though this example focused on a network topology for telecom, the process and technology can be extended to any use case that involves a topology or hierarchy of information that needs to be analyzed in real-time.  
<br>
<br>This repo contains the code used to collect network topology data (using a traceroute script), the Apache Spark code used for the analysis, and the Zeppelin notebook used for data visualization. 
<br>
<br>To Run:
<br>
<br>1. Clone this repo
<br>2. Navigate to the docker directory
<br>3. Execute ./run.sh (You'll need to have <a href="https://www.docker.com/">Docker</a> installed on your machine)
<br>4. 
<br>
<br><b>References:</b>
<br>&bull; <a href="http://zeppelin.apache.org/docs/latest/displaysystem/front-end-angular.html">Apache Zeppelin - Angular (front-end API)</a>
<br>&bull; <a href="http://zeppelin.apache.org/docs/latest/displaysystem/back-end-angular.html">Apache Zeppelin - Angular (back-end API)</a>
