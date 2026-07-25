---
title: "SaveSvgZip"
second_title: "Aspose.PDF untuk Go via C++"
description: "Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai SVG-archive."
type: docs
url: /id/go-cpp/convert/savesvgzip/
---

_Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai arsip SVG._

```go
func (document *Document) SaveSvgZip(filename string) error
```

**Parameters**: 
  * **filename** - new filename

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) membuka PDF-dokumen dengan nama file
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf.Close()
	// SaveSvgZip(filename string) menyimpan PDF-document yang sebelumnya dibuka sebagai arsip SVG dengan nama file
	err = pdf.SaveSvgZip("sample_svg.zip")
	if err != nil {
		log.Fatal(err)
	}
}
```
