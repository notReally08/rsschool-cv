## Rahatsevich Darya

* *e-mail*: dasha.pavlovna2014@yandex.ru
* *telegram*: @df_quimby

I feel like a researcher, very curious one. Since my experience is still just
beginning, my preferences in technology are quite flexible, this means that I
am open to learning new technologies and constantly immersing myself in those
that I already know.
For me, the priority is established communication in the team. I am for positive
criticism without violating personal boundaries. I myself have great respect for
the personal boundaries of others. I can manage on my own and I'm not ashamed
to ask for help when I need it.

**My skill:**
* HTML, CSS, JS, препроцессоры (sass, less), БЭМ
* ReactJS, Redux, Redux-Saga
* webpack, gulp
* Git
* I use VSCode, WebStorm

---
Code example:

```javascript
import { taskList } from "./components/taskList/taskList";
import { localStorageInit } from "./localStorage/storage";
import { getDataFromLocalStorage } from "./localStorage/storage";

function render() {
    const container = document.querySelector(".tasks .container");
    const taskListArray = getDataFromLocalStorage();
    container.innerHTML = taskListArray.length ? taskList(taskListArray) : "Место для твоих задач";
}

function init() {
    localStorageInit();
    render();
}

init();
```

---
**My own projects:**
Vanilla js:
[js-posts](http://jsposts.ge-service.by/) [source code](https://bitbucket.org/some_person/jsposts)

React:
* [learnredux](http://learnredux.ge-service.by/) [source code](https://bitbucket.org/some_person/learnredux)  
* [rm-app](http://rm-app.ge-service.by/) [source code](https://bitbucket.org/jo_barbera/rm-app)

Markup:
[http://aod.ge-service.by/](http://aod.ge-service.by/)
[http://binary.ge-service.by/](http://binary.ge-service.by/)

**Education:**
* Computer Academy ItStep
* Udemy (HTML, CSS)
* Self-study on documentation and courses from youtube

**English level:** *Advanced*
