# Regular Expression
![image](https://user-images.githubusercontent.com/83280369/190268026-fb5ae8c2-1179-47c8-aaca-53c9a84444f6.png)

## PHP Example:
$product_name = ""; //Input String <br>
$product_name = preg_replace("/[\s_()]/", "-", $product_name); <br>
$product_name = preg_replace("/[^A-Za-z0-9(\-)]/", '', $product_name); <br>
$product_name = str_replace( array( '\'', '"', ',' , ';', '<', '>', '.', '%' ), ' ', $product_name); <br>
echo $product_name;

## Reference:
- javaTpoint: https://www.javatpoint.com/regex
