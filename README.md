<!-- The character `|` around a string denotes a place in this markdown file that needs to be changed for each extension. -->
<!-- You may also delete any comments you don't need anymore. -->

# TODO:

- [ ] Replace information in `/README.md`
- [ ] Replace name in `/rollup.config.umd.js`
- [ ] Replace information in `/package.json`
- [ ] Write extension in `/src/index.js`
- [ ] Write tests in `/spec/index.test.js`
- [ ] Uncomment release in `/.github/workflows/main.yml`

<!-- Delete this line and above -->

# marked-|this-extension|
<!-- Description -->

# Usage
<!-- Show most examples of how to use this extension -->

```js
import {marked} from "marked";
import |thisExtension| from "marked-|this-extension|";

// or ES Module script
// import marked from "https://cdn.jsdelivr.net/gh/markedjs/marked/lib/marked.esm.js";
// import |thisExtension| from "https://cdn.jsdelivr.net/gh/markedjs/marked-|this-extension|/lib/index.mjs";

const options = {
	// |default options|
};

marked.use(|thisExtension|(options));

marked.parse("|example markdown|");
// <p>|example html|</p>
```

## `options`

<!-- If there are no options you can delete this section -->
