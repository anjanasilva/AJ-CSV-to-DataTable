# AJ CSV to DataTable

Contributors: anjanasilva
Tags: data, table, csv, import, datatable
Requires at least: 4.3.1
Tested up to: 4.3.1
Stable tag: 4.3

Import data from a CSV file and display it in a DataTable.


## Description

Wordpress Plugin to present a CSV file in a DataTable. This will import data from a CSV file and display in a DataTable.


## How To Use

Insert following code snippet into any page or post using this shortcode, make sure you use an unique id :

`[aj-csv2dt src=http://e-innoving.com/samples/SacramentocrimeJanuary2006.csv id=datatable_id]`

Save it, just refresh the page and see. Less hassle, all your csv data is inside the DataTable.


## Installation

1. Install and activate the plugin via `WP-Admin > Plugins`.
2. Add shortcode to a post or page: 
`[aj-csv2dt src=http://e-innoving.com/samples/SacramentocrimeJanuary2006.csv id=datatable_id]`.

## Credits

This plugin utilizes some excellent open source scripts, functions and images whose creators deserve to be recognized.

1. Shaun Scovil, for inspiring me through his [CSV to Sortable] Plugin.
2. World renowned [DataTables Library] by Alan.
3. V.Krishn wrote a handy [PHP function] that enables users of PHP < 5.3 to utilize the `str_getcsv()` function that powers this plugin.

[CSV to Sortable]: https://wordpress.org/plugins/csv-to-sorttable/
[DataTables Library] : https://www.datatables.net
[PHP function]: http://github.com/insteps/phputils

## Common Errors

1. If the datatable misbehaves, this is probably due to an incorrect csv format. In that case, open csv file in excel
and re-save it as a new csv. Most likely this will resolve your issue.

## Changelog

= 1.0 =
* First public release.