In [1]:                                                                                       
a = ["apple","orange","grape"]                                                         
print(a)                                                                               
['apple', 'orange', 'grape']                                                              
In [3]:                                                                           
a.append("mango")                                                                        
print(a)                                                                                     
['apple', 'orange', 'grape', 'mango', 'mango']                                                
In [4]:                                                                                 
a.extend(["watermelon"])                                                                     print(a)
['apple', 'orange', 'grape', 'mango', 'mango', 'watermelon']                                   
In [7]:                                                                               
a.insert(2,"guava")                                                                
print(a)                                                                                  
['apple', 'orange', 'guava', 'grape', 'mango', 'mango', 'watermelon']                      
In [8]:                                                                                       
a.remove("mango")                                                                          
print(a)                                                                                   
['apple', 'orange', 'guava', 'grape', 'mango', 'watermelon']                             
In [9]:                                                                                
print(len(a))                                                                            
6                                                                                        
In [11]:                                                                                      
a = {1:"natural number",2:"whole number",3:"integer",4:"rational number",5:"irrational number",6:"real number"}                                                                     
print(a)                                                                                    
{1: 'natural number', 2: 'whole number', 3: 'integer', 4: 'rational number', 5: 'irrational number', 6: 'real number'}                                                         
In [12]:                                                                                   
a[4]                                                                                         
Out[12]:                                                                                  
'rational number'                                                                            
In [13]:                                                                                    
a[1]                                                                                      
Out[13]:                                                                                     
'natural number'                                                                           
In [14]:                                                                                     
In [15]:                                                                                    
a.get(1)                                                                                  
Out[15]:                                                                                 
'natural number'                                                                           
In [16]:                                                                                       
a.get(7)                                                                                       
In [18]:                                                                                
print(a.get(7))                                                                           
None                                                                                        
In [19]:                                                                                     
a.get(7,"not found")                                                                        
Out[19]:                                                                                    
'not found'                                                                                   
In [20]:                                                                                       
keys = ["yesobu","rohit","karthik"]                                                        
values = ["python","c","java"]                                                          
In [21]:                                                                                 
data = dict(zip(keys,values))                                                            
In [22]:                                                                                   
print(data)                                                                                
{'yesobu': 'python', 'rohit': 'c', 'karthik': 'java'}                              
In [23]:                                                                                      
data["lovely"] = "cs"                                                                       
In [24]:                                                                                      
print(data)                                                                                  
{'yesobu': 'python', 'rohit': 'c', 'karthik': 'java', 'lovely': 'cs'}                     
In [30]:                                                                                     
s = {11,22,33,44,55}                                                                           
In [26]:                                                                                     
print(s)                                                                                       
[11, 22, 33, 44, 55]                                                                        
In [27]:                                                                                       
print(s)                                                                                    
[11, 22, 33, 44, 55]                                                                        
In [31]:                                                                                  
s = {11,22,33,44,55,44,33,22,11}                                                          
In [29]:                                                                                  
print(s)                                                                                       
[11, 22, 33, 44, 55, 44, 33, 22, 11]                                                           
In [32]:                                                                                       
s = {11,22,33,44,44,33,22,11,55,66,}                                                       
print(s)                                                                                    
{33, 66, 11, 44, 22, 55}                                                                     
In [ ]:                                                                             
