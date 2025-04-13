- ```python
  Import pymysql
  connection = pymysql.connect()
  
  cur = connection.cursor()
  
  cur = execute()
  
  for cedula,nombre in cur.fetchall():
    print(cedula,"/",nombre)
    
  connection.close()
  ```
-