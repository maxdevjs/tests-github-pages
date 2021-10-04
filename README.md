[Demo](https://maxdevjs.github.io/tests-github-pages/)

<link href="styletype.css" rel="stylesheet"></link>

<div>
<p class="line-1 anim-typewriter">Animation typewriter style using css steps()</p>
</div>

<link href="style.css" rel="stylesheet"></link>

<div>
  <p>testing with an orange bg</p>
</div>

<style>
  h1 {
    background-color: navy;
  }
</style>

# tests-github-pages

Testing 💩 for GitHub pages

The previous and this are actaully `<p>`

- This does not work:

```{.red .numberLines startFrom="1"}
Here is a paragraph.

And another.
```

<div id="text">
  <p>this is a `p` in a `div`</p>
  <p>here should be added something with `js`</p>
</div>

<style>
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
</style>

![DNCE’s Waving Pug](https://media.giphy.com/media/3oKIPsx2VAYAgEHC12/giphy.gif){.center}

<script>
  const div = document.querySelector('#text')
  div.style.background = 'red'
  const text = document.createTextNode('some text')
  div.appendChild(text)
</script>

<div id="extern">
  <p>this is a `p` in a `div`</p>
  <p>here should be added something with `js`</p>
</div>

<script src='script.js'>

</script>
