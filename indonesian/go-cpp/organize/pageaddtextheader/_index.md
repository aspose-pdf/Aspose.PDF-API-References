---
title: "PageAddTextHeader"
second_title: "Aspose.PDF untuk Go via C++"
description: "Tambahkan teks di header halaman."
type: docs
url: /id/go-cpp/organize/pageaddtextheader/
---

_Tambahkan teks di header halaman._

```go
func (document *Document) PageAddTextHeader(num int32, header string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **header** - pages header

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
	// PageAddTextHeader(num int32, header string) menambahkan teks di header halaman
	err = pdf.PageAddTextHeader(1, "Header")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
	err = pdf.SaveAs("sample_PageAddTextHeader.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
