---
title: "PageAddText"
second_title: "Aspose.PDF untuk Go via C++"
description: "Tambahkan teks pada halaman."
type: docs
url: /id/go-cpp/organize/pageaddtext/
---

_Tambahkan teks pada halaman._

```go
func (document *Document) PageAddText(num int32, addText string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **addText** - added text

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
	// PageAddText(num int32, addText string) menambahkan teks pada halaman
	err = pdf.PageAddText(1, "added text")
	if err != nil {
		log.Fatal(err)
	}
	// Save() menyimpan PDF-document yang sebelumnya dibuka
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
