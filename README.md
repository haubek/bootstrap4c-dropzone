# Bootstrap4C

### dropzone

The *Bootstrap4C Dropzone* is a simple Bootstrap 4 stylesheet component for the brilliant DropzoneJS library (http://www.dropzonejs.com).

See demo here => https://haubek.github.io

### Yarn install

```
yarn add bootstrap4c-dropzone
```

### CSS

```
<link href="path/to/component-dropzone.css" rel="stylesheet">
```

### HTML5 markup

```
<div id="dropzone" class="dropzone"></div>
```

### Javascript

```
Dropzone.autoDiscover = false;
jQuery(document).ready(function() {
  $("#dropzone").dropzone({
    url: "/file/post",
    dictDefaultMessage: "Drop files here or<br>click to upload..."
  });
});
```

