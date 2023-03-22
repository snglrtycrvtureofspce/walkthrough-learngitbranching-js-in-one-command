# A guide to passing learngitbranching-js with one command

## Getting started

1. Go to [learngitbranching](learngitbranching.js.org) and open the main page with the tasks as shown in the screenshot:
![Illustration](https://github.com/snglrtycrvtureofspce/walkthrough-learngitbranching-js-in-one-command/blob/main/img/mainPage.png)
2. Open the Developer panel (F12 or CTRL + SHIFT + I) and next, select the console tab.
3. Paste the following code (or copy from the file script.js): <br>
```
const elements = document.querySelectorAll(".levelIcon");

for (let i = 0; i < elements.length; i++) {
  elements[i].classList.add("solved");
}
```
4. Everything is ready!
### Relevant on 03/22/2023