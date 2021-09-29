# **SpinProducts with Bootstrap 4.4.1 carousel**

360 spin products with Bootstrap 4.4.1 carousel

# Usage

HTML

```html
...
<div class="carousel-inner">
	<div class="carousel-item spin-products">
		<img src="assets/archive/images01/01.jpeg" alt="" style="width:100%;"/>
	</div>
</div>
...
```

Add css to `<head>`

```html
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">
<link rel="stylesheet" type="text/css" href="assets/css/spin-products.min.css">
```

Add js to `<body>`

```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js" type="text/javascript"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" type="text/javascript"></script>
<script src="js/jquery.spin-products.min.js" type="text/javascript"></script>
```

Add Settings to `<body>` or js file

```jsx
<script>
    $('.spin-products').spinProducts({
        // One path
        // imgPath: 'archive/images',

        // Multiple path
        imgPath: [
            'archive/images01',
            'archive/images02',
            'archive/images03',
        ],
        fileType: 'jpeg',
    });
</script>
```

# Settings

**imgPath**

- **Type:** string or array
- **Default:** 'archive/images'
- **Example:** 'archive/images' or ['path1', 'path2', 'path3']
- Images path

**fileType**

- **Type:** string
- **Default:** 'jpeg'
- Images file type