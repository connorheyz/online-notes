# IB Math 1



<script>
var url = 'http://api.wolframalpha.com/v2/query?appid=244T5E-WP5XR9GQTU&input=france&output=image';

$(document).ready(function(){
$.ajax({ 
    url : url, 
}).always(function(){
    $("#IMAGE_ID").attr("src", url);
    
});	
});
</script>

## Notes

## Study Guides
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTkxNzYwNTg1MiwtMTAzMDEwMjczNywtMj
A4NTAxMjM2NSwtMTE4NDQ4MzAyNCw5MTc1Mzg3MjAsMTI2NzY2
NDIyOF19
-->