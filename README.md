# Projects related to DOM

## project link
[Click here](https://stackblitz.com/edit/dom-project-chaiaurcode?file=index.html)

# Solution code


# Project 1 | ColorChanger

```javascript

const buttons = document.querySelectorAll('.button');

const body = document.querySelector('body')


buttons.forEach( (btn)=> {
    btn.addEventListener('click', (e)=>{
        console.log(e);
        console.log(e.target);

        switch(e.target.id){

            case 'grey':
                // body.style.backgroundColor='gray';
                body.style.backgroundColor= e.target.id;
            break;
            case 'white':
                // body.style.backgroundColor='white';
                body.style.backgroundColor= e.target.id;
            break;
            case 'blue':
                // body.style.backgroundColor='blue';
                body.style.backgroundColor= e.target.id;
            break;
            case 'yellow':
                // body.style.backgroundColor='yellow';
                body.style.backgroundColor= e.target.id;
            break;
            case 'purple':
                // body.style.backgroundColor='purple';
                body.style.backgroundColor= e.target.id;
            break;
        }
    })
})

```
