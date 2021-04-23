# Live_Nested_data
For the live project 

You have two Data file 
- One is Master.json 
- Second one Config.json
- load these using $"import json"$ packages and also using encoding='utf-8'
### Problem statement 
- Working on json file you have list under disctonry file for example 
 * Master.json have : [................{..........}.....]
  * same with config file dict under list .
 ##### Task 
1. You have first the structure or Output.json file for stucture 
2. We want same stucture 
3. You will a $"Master_Id"$ under $Master.json$ file , so now check every "Master_Id" with "Config.json" file "Master_identifier" 
    * For example : if Master[0]['Master_id']==config[0]['Master_idenfier']: so , matched successfull with the Id than 
          *  it created a nested data under 'Master.json' file with config key and created a list under dict of config file data . 
                  * for Example : (key present in master.json file )config: { [list of matched "master_identifier" which present in config.json file ]
