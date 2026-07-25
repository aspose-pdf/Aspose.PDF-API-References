---
title: "PageAddPageNum"
second_title: "Aspose.PDF untuk Go via C++"
description: "Tambahkan nomor halaman pada halaman."
type: docs
url: /id/go-cpp/organize/pageaddpagenum/
---

_Tambahkan nomor halaman pada halaman._

```go
func (document *Document) PageAddPageNum(num int32) error
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
	// PageAddPageNum(num int32) menambahkan nomor halaman pada halaman
	err = pdf.PageAddPageNum(1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
	err = pdf.SaveAs("sample_page1_AddPageNum.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
