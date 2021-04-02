
# OSM x QBUS | BURGERS | Custom Job for McDonalds MLO

#### Specially designed for [THIS MLO](https://www.youtube.com/watch?v=qHw63IeCcJs). 
#### Inspired / Reworked from Taco Job for QBUS, still much different. 

## Features 

#### - Added *Burger Bun Making* as an extra part of the JOB.
#### - Added *DRIVEBY* where other citizens can also buy Burgers (if someone makes burgers)
#### - All other features of TACO JOB intact, optimized slightly, and removed useless stuff. 
#### - Locations adapted well to the Beautiful MLO by [UT MODZ](https://www.youtube.com/channel/UCLyHsvgL80IIatiWyhG-TjA)
#### - New Items added and all the code and images are also attached with the resource. 


## Instructions for Installation / Setup 

#### Item Images are included in the folder `inv-images` | Should be copied into Inventory Images.

#### Add this into your SHARED.LUA (in the CORE FOLDER)

```
["burger"] 		 			 	 = {["name"] = "burger",       		    		["label"] = "Burger",	 					["weight"] = 300, 		["type"] = "item", 		["image"] = "burger.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = false,   ["combinable"] = nil,   ["description"] = "Some big burger brother"},
["bread"] 		 			 	 = {["name"] = "bread",       		    		["label"] = "Raw Bread",	 				["weight"] = 100, 		["type"] = "item", 		["image"] = "bread.png", 				["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false,   ["combinable"] = nil,   ["description"] = "Some big burger brother"},
["bun"] 		 			 	 = {["name"] = "bun",       		    		["label"] = "Bun",	 					["weight"] = 100, 		["type"] = "item", 		["image"] = "bun.png", 				        ["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false,   ["combinable"] = nil,   ["description"] = "Some big burger brother"},
["meat"] 		 			 	 = {["name"] = "meat",       		    		["label"] = "Meat",	 					["weight"] = 100, 		["type"] = "item", 		["image"] = "meat.png", 				["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false,   ["combinable"] = nil,   ["description"] = "Some big burger brother"},
["lettuce"] 	 			 	    = {["name"] = "lettuce",       			        ["label"] = "Lettuce",	 				["weight"] = 100, 		["type"] = "item", 		["image"] = "lettuce.png", 				["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false,   ["combinable"] = nil,   ["description"] = "Some big burger brother"},
["burger-box"] 	 			    = {["name"] = "burger-box",       			        ["label"] = "Burger Box",	 				["weight"] = 100, 		["type"] = "item", 		["image"] = "taco-box.png",     ["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false,                     ["combinable"] = nil,   ["description"] = "Some big burger brother"},
["burger-bag"] 	 			 	  = {["name"] = "burger-bag",       			    ["label"] = "Burger Bag",	 				["weight"] = 100, 		["type"] = "item", 		["image"] = "taco-bag.png", 			["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false,                     ["combinable"] = nil,   ["description"] = "Some big burger brother"},
```
