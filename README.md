# COPY OF SNOWFLKE GUIDE TO REACT 

- Developing React Native Application using Snowflake Hybrid Tables

	https://quickstarts.snowflake.com/guide/developing-react-native-applications-using-hybrid-tables-sql-alchemy-flask/index.html?index=..%2F..index#3


FREE Acccount in SF does not have Hybrid Tables, but the code worked after all troubleshooting. 

There were a lot of changes to be done from the original code. 

A lot of errors with the connection. 

Pay attention to the ACCOUNT LOCATOR

##### TO STARTE THE SERVER: 

- Inside /API:

	run node ./node_modules/serverless/bin/serverless wsgi serve

THEN:

- Inside /UserInterface

	Run npm install

	Run npx expo start --clear and hit w key to run the app in a web browser. 
			
			If you are encountering "Error: error:0308010C:digital envelope routines::unsupported", Run export NODE_OPTIONS=--openssl-legacy-provider


	The application should open in localhost:19006

