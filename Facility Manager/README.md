Facilitity Resource Manager
===

This project is for an application used to track different resources within a facility e.g. an office building. This project consists of an Power Apps application as well as the assiciated tables needed for the application.

# Custom tables
### Facility
This is the master record for one facility to be managed. In this example it holds the bare bones info of the location but could be extended with personnel data for example.

### Room
A space within a facility that holds different resources. The room is also in and of itself considered a resource.

### Resource
The resources to be tracked. For the time being these are things like soap and paper dispensers in washrooms.

### Case
A case / ticket of a certain type. At the moment only service request type cases are planned.

### Resource Activity
Any operation made to a resource. These activities are tracked within a facility and logged using the Power Apps application.