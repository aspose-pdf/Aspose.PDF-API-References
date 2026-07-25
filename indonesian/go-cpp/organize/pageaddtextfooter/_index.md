---
title: "PageAddTextFooter"
second_title: "Aspose.PDF untuk Go via C++"
description: "Tambahkan teks di footer halaman."
type: docs
url: /id/go-cpp/organize/pageaddtextfooter/
---

_Tambahkan teks di footer halaman._

```go
func (document *Document) PageAddTextFooter(num int32, footer string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **footer** - pages footer

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
	// PageAddTextFooter(num int32, footer string) menambahkan teks di footer halaman
	err = pdf.PageAddTextFooter(1, "Footer")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
	err = pdf.SaveAs("sample_PageAddTextFooter.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
