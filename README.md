# Headless Shopping Cart
This was inspired by Snipcart (https://snipcart.com). This is a client side, headless, JavaScript/jQuery shopping cart with CSS styling. If you have access to HTML you can use it.

---

### PolygonPay Installation

1) The first step is to sign up for a [PolygonPay](https://app.polygonpay.com/signup) account and obtain an API key.

2) The second step is to include the following two `<script>` tags and the one `<link>` tag in your HTML `<head>`. In order to optimize performance you should implement the minified versions of jQuery and polygonpayJS just like the ones below.
```html
<script src="https://cdn.jsdelivr.net/gh/jquery/jquery/dist/jquery.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/Seantheprogrammer93/polygonpayjs@v2.0.1-alpha/polygonpay.min.js"></script>
<link rel="stylesheet" crossorigin="anonymous" type="text/css" href="https://cdn.jsdelivr.net/gh/Seantheprogrammer93/polygonpayjs@v2.0.1-alpha/polygonpayjs-style.min.css">
```

3) The last step is to include the following `<div>` tag in the `<body>` of your HTML document.
```html
<div class="polygonpayjs"></div>
```

After you complete steps 1, 2 and 3 your HTML document should look like the example code below. Please, feel free to copy the code below if you want a simple starting point for your HTML document.
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://cdn.jsdelivr.net/gh/jquery/jquery/dist/jquery.min.js"></script>
    <script src="https://cdn.jsdelivr.net/gh/Seantheprogrammer93/polygonpayjs@v2.0.1-alpha/polygonpay.min.js"></script>
    <link rel="stylesheet" crossorigin="anonymous" type="text/css"
        href="https://cdn.jsdelivr.net/gh/Seantheprogrammer93/polygonpayjs@v2.0.1-alpha/polygonpayjs-style.min.css">
</head>

<body>
    <div class="polygonpayjs"></div>

    <button class="button-add" data-title="Shirt" data-description="This is a shirt" data-price="3.75"
        data-url="https://example.com/shirt"
        data-imageSrc="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fdemo.wpstartersites.com%2Fcordero-demo%2Fwp-content%2Fuploads%2Fsites%2F12%2F2020%2F06%2Fmens-tee-blue.jpg&f=1&nofb=1&ipt=3beb7e4030c314bdbafe6cfd288aaadd051db5111832d3023afbf9fcf781c4ed&ipo=images">
        Add to Cart
    </button>

    <button class="button-add" data-title="Hat" data-description="This is hat" data-price="7.14"
        data-url="https://example.com/hat"
        data-imageSrc="https://cdn.shopify.com/s/files/1/1045/5130/products/DB-GD_2000x2000.jpg?v=1544714533">
        Add to Cart
    </button>
</body>

</html>
```

🎉 **Congratulations!** 🎉

You have successfully installed PolygonPay and you will now be able to create your eCommerce store quickly and easily.

---

### How to Use PolygonPay

After you install PolygonPay you will be able to implement a `<button>` in your HTML code to add a product to the PolygonPay cart and checkout. The following `<button>` tag is an example.

```html
<button class="polygonpay-add-item"
        data-title="Hat" 
        data-description="This is a hat"
        data-price="15.79" 
        data-url="https://example.com/hat" 
        data-imageSrc="https://example.com/hat.png">
        Add to Cart
</button>
```
---

### FAQ
- **Where can I use PolygonPay?** - You can use PolygonPay wherever you have direct access to HTML code, this includes frameworks like React and Next.js or WordPress. **If you have direct access to HTML code then you can use PolygonPay**.
- **Is PolygonPay free?** - PolygonPay charges a small fee of 2% on your monthly revenue.
