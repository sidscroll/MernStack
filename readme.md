1. Install MongoDB via Homebrew

	1.	Open Terminal.
	2.	Run the following commands:
```brew tap mongodb/brew
   brew install mongodb-community@6.0```

2. Start the MongoDB Service

	1.	Start the MongoDB server:
`brew services start mongodb/brew/mongodb-community`

	2.	Verify MongoDB is running:
`brew services list`

3. Access MongoDB

	1.	Open the MongoDB shell:
    mongosh

4. Stop the MongoDB Service

To stop the service, run:
brew services stop mongodb/brew/mongodb-community   