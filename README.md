# carrossel

Construção do carrossel usando `Vanilla JavaScript` para o curso Imersão Frontend Ingate-Educa

## Como usar

```html
<link rel="stylesheet" href="carrossel/css.css" />

<div id="carrossel"></div>

<script src="carrossel/index.js"></script>
```

```js
const options = {
  el: document.getElementById("carrossel"),
  images: [
    "https://images-na.ssl-images-amazon.com/images/I/71an9eiBxpL._AC_SL1500_.jpg",
    "https://jp.techcrunch.com/wp-content/uploads/2020/05/00100trportrait_00100_burst20200506153653558_cover.jpg",
    "https://images-na.ssl-images-amazon.com/images/I/71an9eiBxpL._AC_SL1500_.jpg",
    "https://jp.techcrunch.com/wp-content/uploads/2020/05/00100trportrait_00100_burst20200506153653558_cover.jpg",
    "https://images-na.ssl-images-amazon.com/images/I/71an9eiBxpL._AC_SL1500_.jpg",
    "https://jp.techcrunch.com/wp-content/uploads/2020/05/00100trportrait_00100_burst20200506153653558_cover.jpg",
    "https://images-na.ssl-images-amazon.com/images/I/71an9eiBxpL._AC_SL1500_.jpg",
    "https://jp.techcrunch.com/wp-content/uploads/2020/05/00100trportrait_00100_burst20200506153653558_cover.jpg",
    "https://images-na.ssl-images-amazon.com/images/I/71an9eiBxpL._AC_SL1500_.jpg",
    "https://jp.techcrunch.com/wp-content/uploads/2020/05/00100trportrait_00100_burst20200506153653558_cover.jpg",
    "https://images-na.ssl-images-amazon.com/images/I/71an9eiBxpL._AC_SL1500_.jpg",
    "https://jp.techcrunch.com/wp-content/uploads/2020/05/00100trportrait_00100_burst20200506153653558_cover.jpg",
    "https://images-na.ssl-images-amazon.com/images/I/71an9eiBxpL._AC_SL1500_.jpg",
    "https://jp.techcrunch.com/wp-content/uploads/2020/05/00100trportrait_00100_burst20200506153653558_cover.jpg",
  ],
};
const carrossel = new Carrossel(options);
```
