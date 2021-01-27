# mule-stateful

A mule app that demonstrate Persitent Object Storage, and Internal Load Balancing pattern using VM queues.
Create a Cluster and launch the nodes this way:

mule -M-Dnode=<n> -M-Dhttp.port=<port>

http.port defaults to 8081 if not specified.
e.g. if you have a two-node cluster, use for each node (if running on the same machine):

mule -M-Dnode=1 

mule -M-Dnode=2 -M-Dhttp.port=8021
