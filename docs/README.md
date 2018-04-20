---
home: true
actionText: Get Started →
actionLink: /guide/
features:
- title: Simplicity First
  details: Minimal setup with markdown-centered project structure helps you focus on writing.
- title: Vue-Powered
  details: Enjoy the dev experience of Vue + webpack, use Vue components in markdown, and develop custom themes with Vue.
- title: Performant
  details: VuePress generates pre-rendered static HTML for each page, and runs as an SPA once a page is loaded.
footer: MIT Licensed | Copyright © 2018-present Evan You
---
# Wakanda Heritage

## Alert Options

::: tip
This is a tip
:::

::: warning No
This is a warning
:::

::: danger
This is a dangerous warning
:::

### Line highlight in code blocks

``` js{4,2}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```

#### Using Vue in Markdown

{{ 4 + 5 * 9 }}

<span v-for="i in 4">gift</span>

<demo-1/>
