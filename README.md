# Instal React on Chromebook


## Start with your OS update
```
laurentiuspurba@penguin:~$ sudo apt-get install curl gnupg -y
laurentiuspurba@penguin:~$ curl -sl https://deb.nodesource.com/setup_14.x| sudo -E bash -
laurentiuspurba@penguin:~$ sudo apt-get install -y nodejs
```

## Instal node version manager
```
laurentiuspurba@penguin:~$ sudo npm install -g n
```

## Editor
Well, you don't need VS Code, since GitHub has it already. This is how you should do
```
1. Let say you have this GH URL https://github.com/laurentiuspurba/react/blob/main/README.md
2. Change the '.com' to '.dev' then you will have free VS Code
```
Hopefully, It'll still be free :pray:


## Let's do the React app
```
laurentiuspurba@penguin:~$ npx create-react-app my-app
laurentiuspurba@penguin:~$ cd my-app
laurentiuspurba@penguin:~$ npm start
``` 
