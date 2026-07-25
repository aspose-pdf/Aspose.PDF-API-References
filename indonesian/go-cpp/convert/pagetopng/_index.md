---
title: "PageToPng"
second_title: "Aspose.PDF untuk Go via C++"
description: "Konversi dan simpan halaman yang ditentukan sebagai Png-image."
type: docs
url: /id/go-cpp/convert/pagetopng/
---

_Mengonversi dan menyimpan halaman yang ditentukan sebagai Png-image._

```go
func (document *Document) PageToPng(num int32, resolution_dpi int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **resolution_dpi** - resolution in DPI of the resulting file
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
	// PageToPng(num int32, resolution_dpi int32, filename string) menyimpan halaman yang ditentukan sebagai file Png-image
	err = pdf.PageToPng(1, 100, "sample_page1.png")
	if err != nil {
		log.Fatal(err)
	}
}
```
