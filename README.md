# Regular Expression

## PHP Example:
$StrProductName = preg_replace("/[\s_()]/", "-", $ProductInfo->ProductNameEnglish); <br>
$StrProductName = preg_replace("/[^A-Za-z0-9(\-)]/", '', $StrProductName);<br>
$StrProductName = preg_replace("/[%&$@]*/", "", $StrProductName);<br>
$StrProductName = str_replace( array( '\'', '"', ',' , ';', '<', '>', '.', '%' ), ' ', $StrProductName);<br>
