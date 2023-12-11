# Changelog

## [0.8.0] - 2023-12-11

- Add `cell_data_format` option to return data as `Cell` structs instead of values

## [0.7.0] - 2023-10-15

- Improve ZIP file error handling
- Update Saxy XML parser
- Improve UTF-16 support

## [0.6.0] - 2022-10-30

- Update Saxy XML parser

## [0.5.0] - 2022-06-12

- Require Elixir 1.10 to fix publishing of documentation

## [0.4.3] - 2021-02-08

- Improve compatibility with XLSX writers (Excel for Mac, …) which completely omit empty rows in worksheets

## [0.4.2] - 2021-02-09

- Add `skip_row?` callback

## [0.4.1] - 2020-10-15

- Add support for `decimal ~> 2.0`

## [0.4.0] - 2020-06-23

- Add `:supported_custom_format` option to `XlsxReader.open/2`
- Support ISO 8601 and US date/time custom format by default

## [0.3.0] - 2020-05-07

- Add `:only` and `:except` options to `XlsxReader.sheets/2` and `XlsxReader.async_sheets/3`

## [0.2.0] - 2020-04-27

- Add `XlsxReader.async_sheets/3`

## [0.1.4] - 2020-04-24

- Speed-up shared string and styles lookups

## [0.1.3] - 2020-02-26

- Improve compatibility with XLSX writers (Excel, Elixslx, …) which completely omit empty cells in worksheets

## [0.1.2] - 2019-12-30

- Add `String` number type to disable numeric conversions

## [0.1.1] - 2019-12-20

- Improve handling of whitespace in shared strings

## [0.1.0] - 2019-12-16

- Initial release
