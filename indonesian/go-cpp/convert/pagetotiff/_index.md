---
title: "PageToTiff"
second_title: "Aspose.PDF untuk Go via C++"
description: "Konversi dan simpan halaman yang ditentukan sebagai Tiff-image."
type: docs
url: /id/go-cpp/convert/pagetotiff/
---

_Mengonversi dan menyimpan halaman yang ditentukan sebagai Tiff-image._

```go
func (document *Document) PageToTiff(num int32, resolution_dpi int32, filename string) error
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
	// PageToTiff(num int32, resolution_dpi int32, filename string) menyimpan halaman yang ditentukan sebagai file Tiff-image
	err = pdf.PageToTiff(1, 100, "sample_page1.tiff")
	if err != nil {
		log.Fatal(err)
	}
}
```
