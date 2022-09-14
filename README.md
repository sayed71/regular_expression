# Regular Expression
![image](https://user-images.githubusercontent.com/83280369/190268026-fb5ae8c2-1179-47c8-aaca-53c9a84444f6.png)

## PHP Example:
$str = "a4tech %kr <83> comfort key, keyboard;";
$str = preg_replace("/[\s_()]/", "-", $str); <br>
$str = preg_replace("/[^A-Za-z0-9(\-)]/", '', $str);<br>
$str = preg_replace("/[%&$@]*/", "", $str);<br>
$str = str_replace( array( '\'', '"', ',' , ';', '<', '>', '.', '%' ), ' ', $str);<br>
echo $str;
