import mysql.connector
conn = mysql.connector.connect(host='localhost', password='admin', user='root', database='login')
mycursor = conn.cursor()
mycursor.execute("CREATE TABLE hhh (username VARCHAR(255), password VARCHAR(255))")
