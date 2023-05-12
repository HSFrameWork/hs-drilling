Unique and Advance Oil Drilling Job with responsive UI and Compatible with any QBCore and ESX server.


[Installation]
Extract hs-drilling.zip and place it into your resource folder.
Install and ensure dependencies for the resource.
Setupconfig.lua (⚠️see #CONFIGURATION for instructions). 
Addensure hs-drilling to your server start config (place it anywhere below the dependency & framework resources).

[configuration]
Please go through all configurable options & settings in config.lua and config.js and configure them to your server's preferences.
Also please read the comments at the end of each line, for a brief information on what the option does. 

[qb-core/shared/items.lua]
['kerosene'] = {
	['name'] = 'kerosene', 			 	  	  	
	['label'] = 'kerosene', 					
	['weight'] = 0, 		
	['type'] = 'item', 		
	['image'] = 'kerosene.png', 				
	['unique'] = true, 		
	['useable'] = true, 	
	['shouldClose'] = false,   
	['combinable'] = nil,   
	['description'] = 'oil'
},
['gasoline'] = {
	['name'] = 'gasoline', 			 	  	  	
	['label'] = 'gasoline', 					
	['weight'] = 0, 		
	['type'] = 'item', 		
	['image'] = 'gasoline.png', 				
	['unique'] = true, 		
	['useable'] = true, 	
	['shouldClose'] = false,   
	['combinable'] = nil,   
	['description'] = 'oil'
},



[Notes]
This resource is targeted toward ESX and QBCore(New) servers. However, with enough effort, it is possible to get this to work with
other frameworks as long as you are willing to change the necessary events - contact me om discord if you are using different frameworks.