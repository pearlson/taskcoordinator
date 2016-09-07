# Task Coordinator
Actor based task-coordinator where tasks are executed in order of priority. 

This is a generic component based on Akka actors to manage execution of a set of tasks grouped by specific priority order. API provided by component can be used by applications which can be triggered to execute tasks as per the sequence of priority. 

The group of tasks themselves are associated with an entity-event. For example, it can be used when a specific device connects and a set of tasks have to be executed in order for configuring the devices. This example could be very prevalent in scenarios like IoT
