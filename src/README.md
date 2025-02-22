<!-- NOTE: README.md is generated from src/README.md -->

# @codemirror/lang-yaml [![NPM version](https://img.shields.io/npm/v/@codemirror/lang-yaml.svg)](https://www.npmjs.org/package/@codemirror/lang-yaml)

[ [**WEBSITE**](https://codemirror.net/) | [**ISSUES**](https://github.com/codemirror/dev/issues) | [**FORUM**](https://discuss.codemirror.net/c/next/) | [**CHANGELOG**](https://github.com/codemirror/lang-yaml/blob/main/CHANGELOG.md) ]

This package implements YAML language support for the
[CodeMirror](https://codemirror.net/) code editor.

The [project page](https://codemirror.net/) has more information, a
number of [examples](https://codemirror.net/examples/) and the
[documentation](https://codemirror.net/docs/).

This code is released under an
[MIT license](https://github.com/codemirror/lang-yaml/tree/main/LICENSE).

We aim to be an inclusive, welcoming community. To make that explicit,
we have a [code of
conduct](http://contributor-covenant.org/version/1/1/0/) that applies
to communication around the project.

The initial implementation of this package was funded by [Braintrust Data](https://braintrustdata.com/).

## Usage

```javascript
import {EditorView, basicSetup} from "codemirror"
import {yaml} from "@codemirror/lang-yaml"

const view = new EditorView({
  parent: document.body,
  doc: `name: Ferdinand\nage: 93`,
  extensions: [basicSetup, yaml()]
})
```

## API Reference

@yaml

@yamlLanguage

@yamlFrontmatter
