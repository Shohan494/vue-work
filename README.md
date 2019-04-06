- vue js file of local project had to include at the bottom of body tag in html

- dynamic loading data in html

- inserting data as example, for element structure:
```
var app4 = new Vue({
  el: '#app-4',
  data: {
    todos: [
      { text: 'Learn JavaScript' },
      { text: 'Learn Vue' },
      { text: 'Build something awesome' }
    ]
  }
})

```
command:

```
app4.todos.push({ text: 'New item' })
```
- for the next grocery list:
```
app7.groceryList.push({ id: 4, text: 'Whatever' })
```