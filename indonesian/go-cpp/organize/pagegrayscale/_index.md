---
title: "PageGrayscale"
second_title: "Aspose.PDF untuk Go via C++"
description: "Konversi halaman menjadi hitam putih."
type: docs
url: /id/go-cpp/organize/pagegrayscale/
---

_Konversi halaman menjadi hitam putih._

```go
func (document *Document) PageGrayscale(num int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document

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
	// PageGrayscale(num int32) mengonversi halaman menjadi hitam putih
	err = pdf.PageGrayscale(1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
	err = pdf.SaveAs("sample_page1_Grayscale.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
