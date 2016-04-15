# simplehttp
###A simple http tool
 HTTP Client
 * @example
 * Usage:
 * Http::get($url, $params);
 * Http::post($url, $params);
 * Http::put($url, $params);
 * patch, option, head....
 * or:
 * Http::request('GET', $url, $params);
  ```php
  <?php
  use JustMd5\SimpleHttp\Http;

  require 'vendor/autoload.php';
  $Res = Http::request('GET', 'http://f.apiplus.cn/ssq-1.json');
  echo var_export($Res, true), PHP_EOL;
  ```
  ###OR
 ```php
 <?php
 require 'src/Http.php';
 print_r(Http::get('http://f.apiplus.cn/ssq-1.json'));
 ```
 ####enjoy

