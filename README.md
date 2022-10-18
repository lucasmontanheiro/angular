# angular

## installation

Angular is a single-page application client using HTML and Typescript.

- NodeJS: Angular uses Node.js as its base for a large part of its build environment.
- Angular
- IDE

### how to install NPM

**Installing NodeJs**

```
sudo apt-get install curl gnupg -y
curl -sl https://deb.nodesource.com/setup_13.x | sudo -E bash -
sudo apt-get install -y nodejs
```

In my case I didn't have the install script for npm, so got it externally
```
curl -L https://npmjs.org/install.sh | sudo sh
```

**Updating NodeJS**
https://www.freecodecamp.org/news/how-to-update-node-and-npm-to-the-latest-version/


### how to install Angular

```
npm install -g @angular/cli
```
```
ng --version
```

## Running

```
ng new my-first-project
cd my-first-project
ng serve
```

## Resources

- [X][Simplilearn: Angular Tutorial For Beginners | Angular Hello World Program Example Step By Step](https://www.youtube.com/watch?v=TC1oVXlVE3M)
