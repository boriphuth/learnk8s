TL;DR: recap in 5 simple steps
Install mongodb https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/
```
brew tap mongodb/brew
brew install mongodb-community@4.4
brew services start mongodb-community@4.4
brew services stop mongodb-community@4.4
ps aux | grep -v grep | grep mongod
 cat /usr/local/etc/mongod.conf
```

1.``` npm install ```
2.``` node index.js ```
3.``` npm run mongodb ``` 
4. http://localhost:3000 