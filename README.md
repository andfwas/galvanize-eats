# Instructions

~~Fork and clone this repo, fill it out and then submit the response.~~

~~When you have completed the entry ticket and received a 👍 then you will get instructions for the Galvanize Eats project.~~

# Questions

**What is a good workflow for a project?**

* Look at the wireframes and choose one
* Review the stories, and prioritize them
* Start working on the next story in the list

**Write a index.html file that has a hello world h1 tag, and that links to an external stylesheet and external javascript file.**

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="style.css">
    <title></title>
  </head>
  <body>
    <h1>Hello World</h1>

    <script type="text/javascript" src="main.js"></script>
  </body>
</html>
```

**What tag is used to navigate between two different html pages?**

* a

**Is a fetch request synchronous or asynchronous?**

* Asynchronous

**What is the result of the following fetch request? Choose all that apply**

```
fetch(myUrl)
  .then((res) => res.json())
  .then((data) => {
    console.log(data)
  })
  .catch((err) => {
    console.log(err)
  )}
```

* Data is logged out when the fetch succeeds
* An error is logged if there is an error

**Given the following fetch post request, choose all that apply**

```
const data = {
  name: 'Brooks',
  employer: 'Galvanize'
}

fetch(url, {
  method: 'POST',
  body: data
})
  .then((res) => res.json())
  .then((res) => {
    console.log(res)
  })
  .catch((err) => {
    console.log(err)
  })
```

* The object data will be sent to the api
* Any errors that the api responds with will be logged to the console


**What is the following code doing?**

```
const form = document.getElementById('my-form')

form.addEventListener('submit', handleFormSubmission)
```

* Write what the above the code is doing

* The form variable allows the js file to relate to the form with id 'my-form'
When data is inputted into the form and <enter> or click the 'submit' button, the javascript will "listen" for any 'form submissions.'

**What is a promise?**

* An object returned from a function that has a function called then that takes a callback that will be called when the original function is finished

**What does the following code do?**

```
const p = document.createElement('p')
const body = document.getElementsByName('body')[0]

p.innerHTML = 'This is a paragraph'
body.append(p)
```

* Describe what the above code is doing

Creates a variable as a "p-tag" (paragraph).
Creates a variable that can access the body of the html.
Adds text to the p-tag variable.
Appends the body of the html file with thew p-tag including the text within the p-tag previously defined.
