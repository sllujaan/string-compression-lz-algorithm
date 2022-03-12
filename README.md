# string-compression-lz-algorithm
string-compression-lz-algorithm

```html
<!-- in html file -->
<head>
  ...
  <script src="lz-string.js"></script>
  ...
</head>
<body>
  ...
  <script type="text/javascript">
    var string = "This is my compression test.";
    console.log("Size of sample is: " + string.length);
    //console.log(`Size of sample is: ${new Blob([string]).size / 1000}KB`);
    var compressed = LZString.compress(string);
    console.log("Size of compressed sample is: " + compressed.length);
    //console.log(`Size of compressed sample is: ${new Blob([compressed]).size / 1000}KB`);
    string = LZString.decompress(compressed);
    console.log("Sample is: " + string);
  </script>
</body>
```
