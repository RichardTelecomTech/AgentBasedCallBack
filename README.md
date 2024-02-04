# AgentBasedCallBack
Flow that will create a skillset for an agent

Based off of Salesforce case details, if the case owner is not IDLE in Genesys it will prompt the client if they wish to request a callback for the agent for x hours

If Client says yes, it will check / create a callback

After 2 hours it will strip that skillset for any agent to answer the callback
