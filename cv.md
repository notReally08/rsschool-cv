## Rahatsevich Darya

* *e-mail*: dasha.pavlovna2014@yandex.ru
* *telegram*: @df_quimby

I am happy to study frontend, I am fond of practice and I like to understand the topic deeply. I want to be part of a team that works together on a common goal. I prefer friendly and eco-friendly communication. I can quickly learn new technologies to use them. I calmly take criticism of my code, listening to the professional advice of more experienced colleagues.

**My skill:**
* HTML, CSS, JS, препроцессоры (sass, less), БЭМ
* ReactJS, Redux, Redux-Saga
* webpack, gulp
* Git
* I use VSCode, WebStorm

---
Code example:

```javascript
import {AsyncAjax as AsyncAjax} from './AsyncAjax.js';
import {DOM as DOM} from './DOM.js';

export class Comments {
    constructor(postId) {
        this.postId = postId;
        this.dom = new DOM();
        this.ajax = new AsyncAjax();
    }

    async getComments() {
        return await this.ajax.fetchAjax(`https://jsonplaceholder.typicode.com/posts/${this.postId}/comments`)
            .then(comments => {
                // console.log(comments);
                return comments;
            })
            .catch(error => {
                // console.log(error);
                return error;
            });

        // console.log(this.postId, comments);
    }

    createCommentsModalBlock(comment = false) {
        let html = [
            {
                'domEl': 'div',
                'class': 'comments__item comment',
                'childrenElems': [
                    {
                        'domEl': 'p',
                        'class': 'comment__name',
                        'innerText': comment.name
                    },

                    {
                        'domEl': 'p',
                        'class': 'comment__body',
                        'innerText': comment.body
                    },

                    {
                        'domEl': 'span',
                        'class': 'comment__user',
                        'innerText': comment.email
                    },
                ]
            }

        ];

        this.dom.constructorDomTree(html, $('.modal__wrapper'));
    }
}
```

---
**My own projects:**

* [learnredux](http://learnredux.ge-service.by/) [source code](https://bitbucket.org/some_person/learnredux)  
* [rm-app](http://rm-app.ge-service.by/) [source code](https://bitbucket.org/jo_barbera/rm-app)  

**Education:**
* Computer Academy ItStep
* Udemy (HTML, CSS)
* Self-study on documentation and courses from youtube

**English level:** *Advanced*
