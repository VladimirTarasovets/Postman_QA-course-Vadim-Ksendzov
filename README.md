# Postman_QA-course-Vadim-Ksendzov

## Создать запросы в Postman

Protocol: http  
IP: 162.55.220.72  
Port: 5005

==================

### EP_1
Method: GET  
EndPoint: /get_method  
request url params:  
     name: str  
     age: int 
    
response: 
```json
[
    "Str",
    "Str"
]
```
 
<img src="https://fxpics.ru/images/2022/05/10/EP1.png" alt="EP1.png" border="0" />
==================

### EP_2  
Method: POST  
EndPoint: /user_info_3  
request form data:  
 name: str  
 age: int  
 salary: int  
 
 response:  
```json
{"name": name,
    "age": age,
    "salary": salary,
    "family": {"children": [["Alex", 24], ["Kate", 12]],
                "u_salary_1_5_year": salary * 4}}
```

[![EP2.png](https://fxpics.ru/images/2022/05/10/EP2.png)](https://fxpics.ru/image/NWXbu)
==================

### EP_3
Method: GET  
EndPoint: /object_info_1  
request url params:  
     name: str  
     age: int      
     weight: int

response:
```json
{"name": name,
    "age": age,
    "daily_food": weight * 0.012,
    "daily_sleep": weight * 2.5}
``` 

<img src="https://fxpics.ru/images/2022/05/10/EP3.png" alt="EP3.png" border="0" />
==================

### EP_4
Method: GET  
EndPoint: /object_info_2  
request url params:  
     name: str  
     age: int      
     weight: int

response:
```json
{"start_qa_salary": salary,
          "qa_salary_after_6_months": salary * 2,
          "qa_salary_after_12_months": salary * 2.7,
          "qa_salary_after_1.5_year": salary * 3.3,
          "qa_salary_after_3.5_years": salary * 3.8,
          "person": {"u_name": [user_name, salary, age],
                     "u_age": age,
                     "u_salary_5_years": salary * 4.2}
          }
``` 

![EP4.png](https://fxpics.ru/images/2022/05/10/EP4.png)
==================

### EP_5
Method: GET  
EndPoint: /object_info_3  
request url params:  
     name: str  
     age: int      
     weight: int

response:
```json
{"name": name,
          "age": age,
          "salary": salary,
          "family": {"children": [["Alex", 24], ["Kate", 12]],
                     "pets": {"cat":{"name":"Sunny", "age": 3},
                              "dog":{"name":"Luky", "age": 4}},
                     "u_salary_1_5_year": salary * 4}
          }
``` 
<img src="https://fxpics.ru/images/2022/05/10/EP5.png" alt="EP5.png" border="0" />
==================

### EP_6
Method: GET  
EndPoint: /object_info_4  
request url params:  
     name: str  
     age: int      
     weight: int

response:
```json
{"name": name,
    "age": int(age),
    "salary": [salary, str(salary * 2), str(salary * 3)]}
``` 
[![EP6.png](https://fxpics.ru/images/2022/05/10/EP6.png)](https://fxpics.ru/image/NWoJX)
==================

### EP_7  
Method: POST  
EndPoint: /user_info_2  
request form data:  
 name: str  
 age: int  
 salary: int  
 
 response:  
```json
{"start_qa_salary": salary,
          "qa_salary_after_6_months": salary * 2,
          "qa_salary_after_12_months": salary * 2.7,
          "qa_salary_after_1.5_year": salary * 3.3,
          "qa_salary_after_3.5_years": salary * 3.8,
          "person": {"u_name": [user_name, salary, age],
                     "u_age": age,
                     "u_salary_5_years": salary * 4.2}
          }
```
<a href="https://fxpics.ru/image/NWq8W"><img src="https://fxpics.ru/images/2022/05/10/EP7.png" alt="EP7.png" border="0" /></a>
