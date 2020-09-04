import psycopg2
connection = psycopg2.connect(database="Assn2", user="postgres", password="", host="localhost")
cursor = connect.cursor()
cursor.execute("SELECT * FROM city LIMIT 20")
for row in cursor;
	print(row)
	
