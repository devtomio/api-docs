---
title: API Reference

language_tabs:
  - shell: Shell
  - javascript: JavaScript

toc_footers:
  - <a href='https://github.com/slatedocs/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true

code_clipboard: true
---

# Introduction

Welcome to the API Documentation for the 1chi API!

This API Documentation was made with [Slate](https://github.com/slatedocs/slate). Feel free to use this to make your own api documentation!

# Images

## Get a random cat.

```shell
curl "https://api.1chi.tk/cat"
```

```javascript
const fetch = require('node-fetch');

fetch('https://api.1chi.tk/cat')
	.then(res => res.json())
	.then(data => console.log(data));
```

> The above command returns JSON structured like this:

```json
{
	"link": "https://api.1chi.tk/img/cat/cat.png"
}
```
