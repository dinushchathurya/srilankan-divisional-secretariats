<p align="center">
    <img src="https://img.shields.io/badge/version-1.0.0-blue">
    <img alt="Scrutinizer build (GitHub/Bitbucket)" src="https://img.shields.io/scrutinizer/build/g/dinushchathurya/srilankan-divisional-secretariats/main">
    <img alt="Scrutinizer code quality (GitHub/Bitbucket)" src="https://img.shields.io/scrutinizer/quality/g/dinushchathurya/srilankan-divisional-secretariats/main">
    <img alt="GitHub All Releases" src="https://img.shields.io/github/downloads/dinushchathurya/srilankan-universities-faculties-degress/total?style=plastic">
    <img src="https://img.shields.io/badge/dependencies-up%20to%20date-orange">
    <img src="https://img.shields.io/badge/coverage-90%25-yellowgreen">
    <img src="https://img.shields.io/badge/rating-★★★★☆-brightgreen">
    <img src="https://img.shields.io/badge/uptime-100%25-brightgreen">
    <img alt="GitHub issues" src="https://img.shields.io/github/issues/dinushchathurya/srilankan-universities-faculties-degress?style=plastic">
    <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/dinushchathurya/srilankan-universities-faculties-degress?style=plastic">
    <img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/dinushchathurya/srilankan-universities-faculties-degrees?style=plastic">
    <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/dinushchathurya/srilankan-universities-faculties-degress?style=plastic">
    <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/dinushchathurya/srilankan-universities-faculties-degress">
    <a href="https://dinushchathurya.github.io/">
    <img alt="Website" src="https://img.shields.io/website?down_message=red&style=plastic&up_message=online&url=https%3A%2F%2Fdinushchathurya.github.io%2F">
    </a>
    <img alt="Twitter URL" src="https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Ftwitter.com%2FDinushChathurya">
    <img src="https://img.shields.io/badge/made%20with%20love-by%20srilanka-orange">
</p>

# All Srilankan Divisional Secretariat

This includes all Srilankan Divisional Secretariats

### Installation

via composer

`composer require dinushchathurya/srilankan-divisional-secretariats`

### Usage 

```sh 
use Dinushchathurya\Secretariat\Secretariat;

public function exampleFunction(){

    return Secretariat::getProvinces(); // Returns all provinces 
    return Secretariat::getDistricts('Province'); // Returns districts of province 
    return Secretariat::getAuthorities('District'); // Returns district secretariats of a district 
}
```
# Documentataion
You can find the documentation for this package from [here](https://divisional-secretariats.herokuapp.com/documentation) .

# Working demo
You can find the working demo for this package from [here](http://divisional-secretariats.herokuapp.com/) .

# Contributing

Author [Dinush Chathurya](https://dinushchathurya.github.io/)

# License

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Copyright (c) 2021 <a href="https://dinushchathurya.github.io/">Dinush Chathurya</a> and <a href="https://codingtricks.io/">codingtricks.io</a>
