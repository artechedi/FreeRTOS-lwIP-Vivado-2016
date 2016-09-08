In order to make the repository compatible with Vivado 2015.2

1-) Modify in the file freertos_zynq.mld the line 66. Set the standalone OS to the latest "ACTIVE" version.

	For example in Vivado 2015.2 put 
	
	OPTION DEPENDS = (standalone_v5_1)
	
2-) Modify in the file freertos_zynq.tcl the line 64. Set standalone OS to the latest "ACTIVE" version. 

	For example in Vivado 2015.2 put
	
	set standalone_version standalone_v5_1