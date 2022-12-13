# DOM & Data

### Getting Started

1. Fork this repo and `git clone` it down to your computer
1. Open index.html in your browser
1. Write your answers in [script.js](script.js)
1. When you're finished or when time is up, push your work to your remote repo, and file a Pull Request

---

![](https://i.imgur.com/mSSe3EG.png)

Given this array of objects in `script.js`:

``` js
const data = [
  { name: "Megatron", address: "Cybertron" },
  { name: "Some guy", address: "Some street" },
  { name: "Grace Hopper", address: "Arlington, Virginia" },
  { name: "Ching Shih", address: "The High Seas" },
  { name: "Slimer", address: "The Library" },
  { name: "Umbra", address: "The Void" },
  { name: "Hypatia", address: "The Neoplatonic school at Alexandria" },
  { name: "Matt Huntington", address: "Remote" },
  { name: "Ronald McDonald", address: "Casa del McDonalds" },
  { name: "Jem", address: "Starlight Music" }
]
```

Write code that loops over this array, creates the necessary DOM elements, and appends to the `#rolodex` div.

Each item in the array should have this DOM structure (_ewww divitis_):

``` html
<div class="info-container">
  <div class="name">Megatron</div>
  <div class="address">Cybertron</div>
</div>
```

Once every rolodex item has been rendered on screen, your page should appear visually like the screenshot above and your DOM tree should look like so in the dev tools Elements tab:

![DOM](https://i.imgur.com/R69q5w0.png)
