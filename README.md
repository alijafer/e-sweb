Library using to converter text [mustache](https://www.npmjs.com/package/mustache)

npm test 🤐 yess i use test env

i will use js npm to multi language

all text should be in `en.json` and `ar.json`

All page with var in `/public` [url Arabic page](https://github.com/alijafer/e-sweb/tree/multilanguage/public)

```
    "test": "mustache ar.json public/index.html > ar/index.html | mustache ar.json public/page4.html > ar/page4.html | mustache ar.json public/page1.html > ar/page1.html | mustache ar.json public/page3.html > ar/page3.html |mustache ar.json public/page5.html > ar/page5.html | mustache ar.json public/page6.html > ar/page6.html"

```

the output is [ar ](https://github.com/alijafer/e-sweb/tree/multilanguage/ar)and [en ](https://github.com/alijafer/e-sweb/tree/multilanguage/en)

Also, I use [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) to Code formatter

Also, We use style="direction: rtl;"

Finished on Thursday, the twenty-fourth of June, 2021
