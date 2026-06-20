# FXpeek Exchange Rate Widget

Embeddable historical exchange rate widget for finance blogs, spreadsheet templates, ecommerce notes, travel-money guides, and internal dashboards.

The widget is powered by FXpeek:

- Widget page: https://fxpeek.com/en/widget?utm_source=github&utm_medium=repo&utm_campaign=fxpeek_wave1_api_csv&utm_content=exchange_rate_widget
- Embed script: https://fxpeek.com/embed/fxpeek-widget.js
- API docs: https://fxpeek.com/en/api?utm_source=github&utm_medium=repo&utm_campaign=fxpeek_wave1_api_csv&utm_content=exchange_rate_widget_api
- Spreadsheet answer hub: https://fxpeek.com/en/answers/excel-spreadsheet-historical-rates?utm_source=github&utm_medium=repo&utm_campaign=fxpeek_wave1_api_csv&utm_content=widget_excel_sheets_answer
- Annual FX report: https://fxpeek.com/en/reports/2026-historical-fx-reference?utm_source=github&utm_medium=repo&utm_campaign=fxpeek_wave1_api_csv&utm_content=exchange_rate_widget_report

## Quick Embed

```html
<div
  data-fxpeek-widget
  data-from="USD"
  data-to="IDR"
  data-amount="100"
  data-locale="en"
></div>
<script async src="https://fxpeek.com/embed/fxpeek-widget.js"></script>
```

## Options

| Attribute | Example | Notes |
| --- | --- | --- |
| `data-from` | `USD` | Base currency code. |
| `data-to` | `IDR` | Target currency code. |
| `data-amount` | `100` | Amount to convert. |
| `data-locale` | `en` | Supported values: `en`, `zh`, `id`, `vi`, `th`, `tl`. |
| `data-height` | `360` | Optional iframe height in pixels. |
| `data-max-width` | `520px` | Optional iframe max width. |

## Use Cases

- Travel receipt history and old expense notes
- Ecommerce settlement examples
- Spreadsheet and accounting template pages
- Excel and Google Sheets historical FX references
- Regional currency comparison articles
- Lightweight financial data documentation

## Demo

Open `examples/basic-embed.html` in a browser, or paste the snippet into any page that allows third-party scripts.

## Data Note

FXpeek rates are reference data for historical lookup, reporting, spreadsheet, and lightweight API workflows. They are not transaction quotes, settlement rates, tax advice, trading signals, or financial advice.

## License

MIT.
