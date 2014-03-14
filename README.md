This project is a fork off of chetandhembre's screenshot project found here https://github.com/chetandhembre/screenshot. 

This version allows you to get screenshot of any website, save a local copy of the screenshot for faster load time, and display the screenshot on your site.

This function is great for designers/developers to display work in your portfolio without having to manually grab screenshots. 

Here's an example on how to use this function:

```
<?php
include 'screenshot.php';
function test() {
  console.log("notice the blank line before this function?");
}
?>
<img src="<?php echo screenshot("google.com");?>"/>
```

You can also see a working example at http://bencbond.com/#portfolio

Enjoy!

"Ben C. Bond" <bencbond@gmail.com> 