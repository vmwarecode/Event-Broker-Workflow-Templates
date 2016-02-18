# Event-Broker-Workflow-Templates

Template workflows for vRA 7 Event Broker Subscriptions.  Both templates log all of the input payload/ HashMap values, including any child HashMaps, recursively.

* Basic template
  * This is suitable for lifecycle state changes
* Approval template
  * This is for connecting to external systems to determine Approval/Rejection
  * Includes additional cost information that is not part of the default payload
  * Includes error handling for all the noob mistakes I made as I tried out this new functionality!
  * You must configure the vcacCafeHost workflow Attribute to point to a vRA plug-in connection

Download the importable .packages of these workflows at the [VMware Developer Center](https://developercenter.vmware.com/samples?id=916&h=Sample).
