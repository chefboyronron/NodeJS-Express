# Setup Local Environment

1. Install NodeJS current LTS version - [https://nodejs.org/en/]
2. Install Text Editor
3. Install GIT bash latest source release - [https://git-scm.com/]
4. Install MongoDb [https://www.mongodb.com/try/download/community]
	1. Install in the root of your system drive with "mongodb" dir.
	2. Create new directory inside MongoDB system directory
	| mongodb > data      |
	|---------------------|
	| mongodb > data > db |
	|---------------------|
	| mongodb > log       |
	3. Run in CMD
	| Navigate to MongoDB directory | `cd C\:mongodb\Server\4.0\bin` |
	|----------------------------------------------------------------|
	| Run MongoDB                   | `mongod --directoryperdb --dbpath C:\"Program Files"\MongoDB\Server\4.0\data\db --logpath C:\"Program Files"\MongoDB\Server\4.0\log\mongo.log --logappend --rest --install` |
	|----------------------------------------------------------------|
	| Start MongoDB                 | `net start mongodb`            |
	|----------------------------------------------------------------|
	| Stop MongoDB                  | `net stop mongodb`             |
	|----------------------------------------------------------------|
	