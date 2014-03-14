This project is a fork off of chetandhembre's screenshot project found here https://github.com/chetandhembre/screenshot. This version allows you to get screenshot of any website, save a local copyof the screenshot for faster loadtime and display it on the site.

Here's an example on how to use this fuction:

```
<?php
include 'screenshot.php';
function test() {
  console.log("notice the blank line before this function?");
}
?>
<img src="<?php echo screenshot("google.com");?>"/>
```
And thats it. Enjoy!

"Ben C. Bond" <bencbond@gmail.com> 