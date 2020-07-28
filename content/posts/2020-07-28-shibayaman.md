---
date: 2019-07-31T22:43:31Z
title: コードスニペットかけるようにしてみたお
author: shibayaman
hero_image: "/content/images/max-di-capua-AhHICglxxx8-unsplash.jpg"

---

    ```javascript
    const helloWorld = () => {
      return 'hello world';
    }

    //この行はハイライトされます
    const iAmHighlighted = true; // highlight-line

    const iAmNotHighlighted = 'hogefugapiyopiyo';
    ```
って書くと

```javascript
const helloWorld = () => {
  return 'hello world';
}

//この行はハイライトされます
const iAmHighlighted = true; // highlight-line

const iAmNotHighlighted = 'hogefugapiyopiyo';
```
って色付きで表示してくれるようにしてみたよん。<br>
コードを書き残したいときは活用してくだされ。