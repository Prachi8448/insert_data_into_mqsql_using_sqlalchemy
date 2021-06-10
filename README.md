# insert_data_into_mqsql_using_sqlalchemy

from sqlalchemy import insert

stmt = insert(employee).values(id=1,name= 'Prachi', salary=50000.00, active=True)

result = connection.execute(stmt)

print(result.rowcount)
