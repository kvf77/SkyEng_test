# SkyEng_test

include "CalcBigNumbersAsString.php";

$str1 = "99999999991234";

$str2 = "88888888881234";

$calc = new CalcBigNumbersAsString();

echo $calc->GetSum($str1, $str2);
