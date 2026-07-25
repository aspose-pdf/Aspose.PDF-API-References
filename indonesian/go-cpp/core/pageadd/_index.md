---
title: "PageAdd"
second_title: "Aspose.PDF untuk Go via C++"
description: "Tambahkan halaman baru dalam PDF-dokumen."
type: docs
url: /id/go-cpp/core/pageadd/
---

_Tambahkan halaman baru dalam dokumen PDF._

```go
func (document *Document) PageAdd() error
```

**Parameters**: 

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
	// PageAdd() menambahkan halaman baru dalam dokumen PDF
	err = pdf.PageAdd()
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
