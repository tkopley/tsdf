# tsdf
Time-Series Data Format for Semiconductor Reliability Data
TSDF is a data format for reliability degradation data, specifically degradation data from semiconductor devices. It aims to take a potentially large amount of reliability data and put it into a small number of files that are human readable. TSDF does this by separating metadata from raw data. With this separation, it is easy for a user to view or search through a set of TSDF files to get information needed to put the data in context (process, lot and wafer info, device types, failure mechanism, etc.)

Based on this data format, software tools such as conversion programs, database management tools, and data analysis tools will be developed and distributed to the user community. Extensions to handle detailed device parameter information, detailed stress waveforms, and semiconductor package information are being planned.
