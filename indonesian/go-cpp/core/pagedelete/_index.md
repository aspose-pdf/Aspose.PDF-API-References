---
title: "PageDelete"
second_title: "Aspose.PDF untuk Go via C++"
description: "Hapus halaman yang ditentukan dalam PDF-dokumen."
type: docs
url: /id/go-cpp/core/pagedelete/
---

_Hapus halaman yang ditentukan dalam PDF-document._

```go
func (document *Document) PageDelete(num int32) error
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
	// PageDelete(num int32) menghapus halaman yang ditentukan dalam PDF-document
	err = pdf.PageDelete(1)
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
