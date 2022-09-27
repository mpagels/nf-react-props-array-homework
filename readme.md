# Quick homework

this homework should help to deepen the topics components, props and arrays. Therefore you MUST use at least on `component` that you wrote, `props` and the given `array` to solve this homework.

## Prepare the quick homework
- create a local react app with the `npx` command, name it `quick-homework`
- after that, create an `assets` folder inside your `src` folder in your react folder structure and move the `persons.js` file (find it in Slack thread or download it here: [right click and Save as...](https://github.com/mpagels/nf-react-props-array-homework/raw/main/persons.js)) into it
- in your `App.js` file, copy this import line at the top of the file
```js
import { persons } from "./assets/persons";
```
- check the content of the `persons.js` file just out of curiosity

## Do the quick homework
- create a `list` of `persons` in react
- The list should display the `name` and an `image` of the person
- use the `status` information to change the background color of the persons `list` item
- if alive -> green
- if dead -> red
- if unknown -> grey

### Tips
- commit small steps and as much as possible (use meaningful commit messages)
- you could try to use branches as well ;-)
- no special styling is needed (execpt the background color ;-) )
- create and use a component (like `<Person />` ) and pass `props` to it

## After finishing the quick homework
- create a GitHub repo 
- and connect it with your local repo
- push your work to GitHub
- post your repo into the Slack thread
