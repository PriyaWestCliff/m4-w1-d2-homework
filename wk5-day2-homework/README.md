# Part 2 – Vue Arrays, Event Listeners, and Hooks

## Objective
The objective of Part 2 is to understand how to:
- Render arrays using Vue
- Add new items to an array
- Compare vanilla JavaScript event listeners with Vue-based event handling
- Transition from plain JavaScript to Vue while preserving earlier code for reference



## Technologies Used
- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Vue.js 2 (via CDN)



## Initial Setup
- A Vue instance is created and bound to `#root`
- A data property called `shoplist` stores grocery items
- The list is rendered dynamically using `v-for`

```js
data: {
  shoplist: ['Salad', 'Eggs', 'Apples', 'Chicken']
}
