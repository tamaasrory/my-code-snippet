

Filter and Find string with preg_match
```php
<?php
$data = ["33.01.03", "01.33.02", " 01.01.33", "33.02.01"];
$find = array_filter($data, fn ($v) => preg_match('(^33[.])', $v));

var_dump($find);

// OUTPUT : 
// ------------------
// array(2) {
//  [0]=> string(8) "33.01.03"
//  [3]=> string(8) "33.02.01"
// }
```

Know more about me pls visit : [my website](https://tamaasrory.com)