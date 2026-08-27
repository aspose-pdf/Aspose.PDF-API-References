---
title: "PageToPdf"
second_title: "Aspose.PDF untuk Go via C++"
description: "Konversi dan simpan halaman yang ditentukan sebagai Pdf."
type: docs
url: /id/go-cpp/convert/pagetopdf/
---

_Mengonversi dan menyimpan halaman yang ditentukan sebagai Pdf._

```go
func (document *Document) PageToPdf(num int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
	// PageToPdf(num int32, filename string) menyimpan halaman yang ditentukan sebagai file Pdf
	err = pdf.PageToPdf(1, "sample_page1.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
