
How do you test that a Flow failed? 
Use the Configure Run After Setting in a Connector!
Create a connector for the sole purpose of runing in the even of a failure of the Flow. If your Flow fails, for whatever reason, the connector that has been configured "to run after a fail", will run. That connector can be, for example, a Send a message to Teams" notifying you that the Flow failed. 
