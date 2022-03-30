# py-styles
Raw CSS to make your site look like python code. Built mainly for my portfolio & will be missing functionality. Feel free to submit a PR or request functionality in a issue.

## Preview
![preview of my portfolio](https://i.imgur.com/5UaoHzV.png)

[Live preview](https://wardpearce.com)


## Documentation
All the python related styling is kept [here](/assets/css/python.css), feel free to use it in your own site.

### Defining functions & returns
```html
<h3 id="about" class="def return-str">about</h3>
```
![preview of def return](https://i.imgur.com/IlAlCu4.png)

#### Return types
- `return-str`
- `return-int`
- `return-list`
- `return-none`
- `return-dict`

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

### Variables
#### Assigning
```html
<div class="var"><p class="name">paaster</p><div class="bool-true"></div></div>
<div class="var"><p class="name">unofficial_dathost_interface</p><div class="bool-false"></div></div>
```
![Bool](https://i.imgur.com/ke6809p.png)

#### Bool
```html
<div class="var"><p class="name">paaster</p><div class="bool-true"></div></div>
<div class="var"><p class="name">unofficial_dathost_interface</p><div class="bool-false"></div></div>
```
![Bool](https://i.imgur.com/ke6809p.png)

#### Dict
```html
<div class="dict">
    <ul>
        <li>
            <p class="str">email</p>
            <p class="str"><a href="mailto:wardpearce@pm.me">wardpearce@pm.me</a></p>
        </li>
        <li>
            <p class="str">matrix</p>
            <p class="str"><a href="https://matrix.to/#/@wardp:matrix.org" target="_blank">@wardp:matrix.org</a></p>
        </li>
        <li>
            <p class="str">github</p>
            <p class="str"><a href="https://github.com/WardPearce/" target="_blank">github.com/WardPearce</a></p>
        </li>
    </ul>
</div>
```
![Dict](https://i.imgur.com/Eglb0q1.png)

#### List
```html
<div class="list">
    <ul>
        <li><p class="str">Python</p></li>
        <li><p class="str">Typescript</p></li>
        <li><p class="str">Svelte</p></li>
        <li><p class="str">MySQL</p></li>
        <li><p class="str">Asyncio</p></li>
        <li><p class="str">Docker</p></li>
        <li><p class="str">Django</p></li>
        <li><p class="str">Vue</p></li>
        <li><p class="str">MongoDB</p></li>
        <li><p class="str">AWS</p></li>
        <li><p class="str">Linux</p></li>
        <li><p class="str">REST APIs</p></li>
        <li><p class="str">Nginx / Apache</p></li>
        <li><p class="str">S3</p></li>
        <li><p class="str">Backblaze</p></li>
        <li><p class="str">SqlAlchemy</p></li>
    </ul>
</div>
```
![List](https://i.imgur.com/5KPaKjH.png)

#### String
```html
<p class="str">Modern typed requests for Python 3 built on-top of HTTPX.</p>
```
![string](https://i.imgur.com/ONL1Hss.png)

#### Integer
```html
<p class="int">0</p>
```
![int](https://i.imgur.com/o5G6jsA.png)

### Return
```html
<div class="return">
    <p class="str">Modern typed requests for Python 3 built on-top of HTTPX.</p>
</div>
```
![Return](https://i.imgur.com/8uKdf6f.png)

### Call
```html
<p class="call">about</p>
```
![Call](https://i.imgur.com/IfmapAe.png)

### Conditionals
Conditionals is the most complex part of `py-styles`, basically every 2nd `li` is treated as the logic for the conditional defined in the `li` above it.

Adding the `else` class to the `li` & leaving it blank is how you define a `else`, otherwise it will be a `elif`.

```html
<div class="conditional">
    <ul>
        <li>paaster</li>
        <li>
            <p class="comment">
                <a href="https://github.com/WardPearce/paaster" target="_blank">https://github.com/WardPearce/paaster</a>
            </p>
            <div class="return">
                <p class="str">Paaster is a secure by default end to end encrypted pastebin built with the objective of simplicity.</p>
            </div>
        </li>

        <li>unofficial_dathost_interface</li>
        <li>
            <p class="comment">
                <a href="https://github.com/UnofficialDathost/Interface" target="_blank">https://github.com/UnofficialDathost/Interface</a>
            </p>
            <div class="return">
                <p class="str">Improved serverless interface for Dathost!</p>
            </div>
        </li>
    </ul>
</div>
```
![conditionals](https://i.imgur.com/WTwwydD.png)