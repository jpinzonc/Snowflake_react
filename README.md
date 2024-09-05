# COPY OF SNOWFLKE GUIDE TO REACT 

- Developing React Native Application using Snowflake Hybrid Tables

	https://quickstarts.snowflake.com/guide/developing-react-native-applications-using-hybrid-tables-sql-alchemy-flask/index.html?index=..%2F..index#3



FREE Acccount in SF does not have Hybrid Tables, but the code worked after all troubleshooting. 

There were a lot of changes to be done from the original code. 

Instead of installing from requirements, create environment and install as modelu not found error appears. This reduces the errors connecting to snowflake. 

A lot of errors with the connection. 

Pay attention to the ACCOUNT LOCATOR

##### TO START THE SERVER: 

You need to run two steps in two separate terminals: 

1. Inside /API run

	node ./node_modules/serverless/bin/serverless wsgi serve

2. Inside /UserInterface run: 

	npm install

	then run: 
	
	npx expo start --clear -- and hit w key to run the app in a web browser. 
	
	If you are encountering "Error: error:0308010C:digital envelope routines::unsupported", Run export NODE_OPTIONS=--openssl-legacy-provider


	The application should open in localhost:19006

