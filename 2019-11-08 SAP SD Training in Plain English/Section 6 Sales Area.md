
There are 3 components in SD:     
finance, sales and logistics    

### finance   

company -> company codes

### Sales Area 

Sales Area = Sales Org + Distribution Channel + Division     
sales org -> distribution channel -> division    
Sales Org = Sales policies 

sales area ~ sales office  
Sales office -> sales group -> sales person   

### Logistics

company code (finance) ~ sales org + distribution channel ~ plant   
plant -> storage location    

### Configuration   

tips: if you see "maganifying glass", it would be safer to copy the configuration.   

【SPRO】 IMG: enterprise structure   
**creation**   
-> sales and distribution   
-> copy sales org. 0001 to "WEST"  
-> copy distribution channel 01 to "AG"   
-> create a new division "XR"   
-> create sales office "BAYA"   
-> create sales group   
-> copy plant 0001 to "NEWJ" (New Jersey)    
-> create storage location "JERC"
-> (optional) copy warehouse 001 to "WH1"    
-> copy shipping point from 0001 to "SENS"  
**Assignment**   
(delete unnecessary assignments)    
-> assign sales org "WEST" to company code 1000  
-> assign sales org to distribution channel "AG"     
-> assign sales org to division "XR"      
-> assign sales office "BAYA" (Bay Area)  
-> assign sales office to sales group "CON"   
-> assign sales org/ditribution channel to plant "NEWJ"   
-> assign plant to storage location "JERC"   
-> assign shipping plant to shipping point "SENS"   

【SE01】 transport organizer   

35. Common (Reference) distribution channels and divisions     
S.Org, D.Chnl, Division    
1000, 10, 00   
1000, 12, 00 (refers to row 1)   
1000, 13, 00 (refers to row 1)   

### Why is enterprise structure created?   
1. reporting: internal vs. external      
2. operational   




























   