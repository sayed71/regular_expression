# Regular Expression

## PHP Example:
$StrProductName = preg_replace("/[\s_()]/", "-", $ProductInfo->ProductNameEnglish);
$StrProductName = preg_replace("/[^A-Za-z0-9(\-)]/", '', $StrProductName);
$StrProductName = preg_replace("/[%&$@]*/", "", $StrProductName);
$StrProductName = str_replace( array( '\'', '"', ',' , ';', '<', '>', '.', '%' ), ' ', $StrProductName);
