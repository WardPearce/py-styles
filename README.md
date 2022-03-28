# py-styles
Raw CSS to make your site look like python code. Built mainly for my portfolio & will be missing functionality. Feel free to submit a PR or request functionality in a issue.

## Preview
![preview of my portfolio](https://i.imgur.com/9chBLhu.png)

[Live preview](https://wardpearce.com)


## Documentation
All the python related styling is kept [here](/assets/css/python.css), feel free to use it in your own site.

### Defining functions & returns
```html
<h3 id="about" class="def return-str">about</h3>
```
#### Preview
![preview of def return](https://i.imgur.com/IlAlCu4.png)

### Adding docstrings
```html
<h3 id="about" class="def return-str">about</h3>
<div class="func">
    <p class="docstring">Who I am.</p>
</div>
```
![Adding docstrings](https://i.imgur.com/AleSRap.png)

### Comments
Will underline if link provided.
```html
<p class="comment">
    <a href="https://github.com/WardPearce/Paycord" target="_blank">https://github.com/WardPearce/Paycord</a>
</p>
```
![Example of comment](https://i.imgur.com/OjriBfb.png)
