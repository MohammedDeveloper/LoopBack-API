#Loop Back API - meetupz

npm install -g loopback-cli
npm install
cd <project>
node .

## MONGO DB
Install Mongo DB - https://www.mongodb.com/
cd C:\MongoDB\bin
mongod --directoryperdb --dbpath C:\MongoDB\data\db --logpath C:\MongoDB\log\mongo.log --logappend --rest --install
net start mongodb
mongo

## Install loopback connector - MongoDB
npm install --save loopback-connector-mongodb

lb datasource mongoDS --connector mongoDB
host: localhost
port: 27017
db: meetupz

## Model
lb model

## Set ACL
lb acl


