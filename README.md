# Blockchain Registry

## The problem
To deliver carVertical customers’ needs of full and comprehensive vehicle historic data, it was identified a need to handle data in a specific manner. There is indication that data can come to carVertical blockchain registry asynchronously, meaning there would be missing history points that would be filled at a later stage. However, due to an intrinsic nature of how blockchain stores data, one axis of timeseries may not be sufficient to achieve full historical events integrity. Thus, a need to introduce a bitemporal capability of some sort that could:

*	Manage missing data points to achieve a comprehensive sorted history of vehicle data
*	potentially achieving an optional audit trail to see how “data looked at a certain point in time”


## Proposals

