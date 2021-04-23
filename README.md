# Live_Nested_data
For the live project 

You have two Data file 
- One is Master.json 
- Second one Config.json
- load these using $"import json"$ packages and also using encoding='utf-8'
- Check the structure of Ouput.json file 
### Problem statement 
- Working on json file you have list under disctonry file for example 
 * Master.json have : [................{..........}.....]
  * same with config file dict under list .
  * Ouput.json for the final result.
 ##### Task 
1. You have first the structure or Output.json file for stucture 
2. We want same stucture as the output.json as 
3. You will a $"Master_Id"$ under $Master.json$ file , so now check every "Master_Id" with "Config.json" file "Master_identifier" 
    - For example : $if Master[0]['Master_id']==config[0]['Master_idenfier']$: so , matched successfull with the Id than 
          *  it created a nested data under 'Master.json' file with config key and created a list under dict of config file data . 
           * for Example : (key present in master.json file )config: { [list of matched "master_identifier" which present in config.json file ]
### Conculusion
- You have fist get and clean the Master.json file and config.json file for final ouput 
- Than created a $"ROOT"$ Dict. where all the data store and than put "$MASTER$" data under the $ROOT$ and under "MASTER " Put the 
-  matched data of $"CONFIG"$.

