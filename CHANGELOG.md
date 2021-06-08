# Changelog

## 1.0.14 (2021-06-08)

* Added *mailto* hyperlinks support (thx Howard Martin)
```php
SimpleXLSXGen::fromArray([
	['Mailto hyperlink', '<a href="mailto:sergey.shuchkin@gmail.com">Please email me</a>']
])->saveAs('test.xlsx');
```
## 1.0.13 (2021-05-29)

* Fixed hyperlinks in several sheets
* Added [Opencollective donation link](https://opencollective.com/simplexlsx)

## 1.0.12 (2021-05-19)

* Fixed hyperlink regex

## 1.0.11 (2021-05-14)

* Fixed 0.00% format, thx [marcrobledo](https://github.com/shuchkin/simplexlsxgen/pull/34), more examples in README.md

## 1.0.10 (2021-05-03)

Stable release

* Added hyperlinks and minimal formatting

## 0.9.25 (2021-02-26)

* Added PHP Datetime object values in a cells

## 0.9.24 (2021-02-26)

* Percent support


## 0.9.23 (2021-01-25)

* Fix local floats in XML


## 0.9.22 (2020-11-04)

* Added multiple sheets support, thx [Savino59](https://github.com/Savino59), class ready for extend now
 
## 0.9.21 (2020-10-17)

* Updated images

## 0.9.20 (2020-10-04)

* Disable type detection if string started with chr(0)

## 0.9.19 (2020-08-23)

* Numbers like SKU right aligned now

## 0.9.18 (2020-08-22)

* Fixed fast shared strings index
 
## 0.9.17 (2020-08-21)

* Fixed real numbers in 123.45 format detection, fast shared strings index (thx fredriksundin)
 
## 0.9.16 (2020-07-29)

* Fixed time detection in HH:MM:SS format

## 0.9.15 (2020-07-14)

* Escape of shared strings for special chars in cells [#1](https://github.com/shuchkin/simplexlsxgen/issues/1) 

## 0.9.14 (2020-05-31)

* Fixed num2name A-Z,AA-AZ column names, thx Ertan Yusufoglu

## 0.9.13 (2020-05-21)

* If string more 160 chars, save as inlineStr

## 0.9.12 (2020-05-21)

* Readme fixed

## 0.9.11 (2020-05-21)

* Removed XML unimportant attributes

## 0.9.10 (2020-05-20)

* Initial release