# Mini_JS

### get only file from browse file use jquery

```sh

$("input[type=file]").on("change", function() {
	var text = $(this).get(0).files[0].name;
	
	//set target display file
	//$(this).siblings("input").val(text);
});

```
