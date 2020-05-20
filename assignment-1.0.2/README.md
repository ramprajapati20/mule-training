mulesoft-activemq-publish-subscribe
Mulesoft application for reading xml post data from HTTP request and publish to activemq. another flow subscribe to activemq to read the queue.

We need to expose an in Mule with RAML implementation (Preferably use XML file )
Transform the XML data into JSON (take any sample json file)
Publish the data into Queue (Install Active MQ)
Subscribe the data from Queue
Call the endpoint (http://httpbin.org/get)