## 💧 plop-helper-date

<a href="https://npmjs.com/package/@piperguy/plop-helper-date">
    <img alt="npm" src="https://img.shields.io/npm/v/@piperguy/plop-helper-date.svg?style=flat-square">
</a>

<a href="https://npmjs.com/package/@piperguy/plop-helper-date">
    <img alt="npm" src="https://img.shields.io/npm/dt/@piperguy/plop-helper-date?style=flat-square">
</a>

_A [plop][plop] helper to grab the current date._

### 📦 Installation

This package is installable from [npm][npm].

```bash
npm install --save-dev @piperguy/plop-helper-date
```

### 🥑 Usage

Before you can use the `plop-pack`, you have to load it into the `plop` object.

```javascript
plop.load("@piperguy/plop-helper-date")
```

Once loaded, you now have access the following helpers.

#### `date`

Creates a formatted date.

**input**

```json
{}
```

**helper**

```handlebars
{{date}}
```

**output**

```javascript
"2020-07-10"
```

### ❔ Questions

🐛 report bugs by filing [issues][issues]  
📢 provide feedback with [issues][issues] or on [twitter][twitter]

[plop]: https://plopjs.com
[npm]: https://npmjs.com
[piperguy]: https://piperguy.github.io
[issues]: https://github.com/@piperguy/plop-helper-date/issues
[twitter]: https://twitter.com/_PiperGuy_
