# entity-alerting
This contet pack works over the top of the ISTI CP for monitoring an alerting.

It enables the following
* create episodes from entity and KPI state changes
* suppress initial actions and repeating alerts for n minutes per KPI, controlled via extensions to itsi_kpi_attributes
* adds additional metadata to the episode contact map
* provides testing services to review fuctionality
* includes a testing dashboard to validate episode lifecycle
* event types (ie groupingid) is the alertable object
* Return to normal rule closes the episode when all event types are OK
