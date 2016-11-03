# Mini_JS

### get only filename from browse file use javascript

```sh

$("#fileUpload").on("change", function(e) {
  console.log(document.getElementById(this.id).files[0].filename);
});

```

### get only file from browse file use jquery

```sh

$("#fileUpload").on("change", function(e) {
			console.log($(this).get(0).files[0].name);
});

```
