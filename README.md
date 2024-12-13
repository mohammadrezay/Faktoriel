# Faktoriel.php
https://quera.org/problemset/589
<?php
$number = readline(" enter a number: ");
function factorial($number) { 
    if ($number == 0) { 
        return 1; 
    } else { 
        return ($number * factorial($number - 1)); 
    } 
}
echo factorial($number);
