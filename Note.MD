# Notes

Module 5

---

Module 4

---

## How to Run the app.js File in Replit

<https://replit.com/talk/ask/How-can-a-change-the-js-what-I-want-run/115881>

## enabling running scripts

<https://www.sharepointdiary.com/2014/03/fix-for-powershell-script-cannot-be-loaded-because-running-scripts-is-disabled-on-this-system.html>

## installing packages with node

npm install -g nodemon

## Sending an HTML File to the Browser

~~~ javascript
// set header content type
res.setHeader(`Content-Type`, `text/html`);

// snd an html file
fs.readFile(`./views/index.html`, (err, data) => {
    if (err){
        console.log(err);
        res.end();
    }
    else{
        res.write(data);
        res.end();
    }
})
~~~

## Sending HTML to The Browser

~~~ Javascript
// set header content type
res.setHeader(`Content-Type`, `text/html`);

res.write(`<head><link rel="styleshet href="#></head>`);
res.write(`<p>Hello, ninjas</p>`);
res.write(`<p>Hello again, ninjas</p>`);
res.end();
~~~
