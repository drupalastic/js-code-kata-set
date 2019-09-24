# Set up code kata's in you local system

I prefer this against online platforms for four main reasons :
1. Its easier to use browsers dev tools to debug things
2. Its closer to real world
3. Live reload / refresh is a real time saver
4. I can use my favourite text editors live templates / snippets while practicing

recommended node version : 12.3.1 (We recommend NVM)

setup :
clone the repository
run `npm install`

once install completes
run `gulp watch`

index.html and script.js is used as it is. 
JS files are not processed because most browsers supports latest JS features. In case you are an IE-11 user - you may consider using https://github.com/drupalastic/HTML-SCSS-JS-Starterkit 

style.scss will be compiled to style.css. Browser will refresh automatically on change. 

# Javascript code kata sets

Most of the times we will be using chrome's console and dev tools. So this following setup works well.
![](.README_images/editor-browser-setup.png)

## JS Code kata 1. Implement a linear search using simple iterative loops.

```$xslt
function linerSearch(list, item) {
  // your code here
}

console.log('liner search result => ', linerSearch([2, 6, 7, 90, 103], 90));

// it must log liner search => 3 (index of 90)
```

## JS Code kata 2. Implement a binary search. We need cut our list to half on every iteration. 

```$xslt
function binarySearch(list, item) {

}

console.log('binary search result => ', binarySearch([2,6,7,90,103,105],90));
// it must log the index of item in the list
```

