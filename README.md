# [DEPRECATED] CIK react

tools library to connect flows with react project.

## hooks

* `useCIKFlow(data: object)` - this hook execute a flow with initial data, the data object should contain `flowName` member in order to activate the specific flow. it can also contain additional data for the flow.

## actions

* `ask_server` - this action send a websocket message to the server and return the flow data that have been received from the server, therefore we can combine server client flows.