# `J001`: TODO app
The task is divided into parts each harder than the previous.
Optional parts are not required to do, but it's going to be ***a big plus***
for you.

### Requirements
+ ***`React`/`Vue`***
+ ***`fetch` API***

### Deadline `3-5 days`

# FAQ
+ ***Can i use other static site generators like `next.js`, `nuxt.js` and etc*** - `No`
+ ***Can i use project generators like `create-react-app`*** - `Yes`
+ ***Can i use Typescript, Flow and etc?*** - `Yes`
+ ***Can i use state managers like Mobx, Redux and etc?*** - `Yes`

# API
+ Official docs: https://github.com/typicode/json-server
+ URL: https://jsonplaceholder.typicode.com/todos

---

### Part `1`
App with the only page that fetches and renders `TODO` list from `API` result.

### Part `2`

###### Optional

Paginate `TODO` list using the `json placeholders` api.
[Request example `/todo?_page=1&_limit=10`](https://jsonplaceholder.typicode.com/todos?_page=1&_limit=10)

***TIP***: Use path parameter `/:page` and check `match.params` object in your properties.