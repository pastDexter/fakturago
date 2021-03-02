# Fakturago 📄

![Go badge](https://img.shields.io/github/go-mod/go-version/pastDexter/fakturago)

CLI for generating invoices from template.
Written in Go.

#### Features:
- [x] YAML templates
- [x] UTF-8 support
- [x] i18n (`en`, `pl`)

## Build

```
go build ./cmd/fakturago
```

## Usage

```
./fakturago --lang en --out invoice_en.pdf ./example.yaml
```
