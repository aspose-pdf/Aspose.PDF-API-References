---
title: "AppendPages"
second_title: "Aspose.PDF untuk Go via C++"
description: "Tambahkan halaman terpilih dari dokumen PDF lain."
type: docs
url: /id/go-cpp/core/appendpages/
---

_Menambahkan halaman terpilih dari PDF-document lain._

```go
func (document *Document) AppendPages(anotherdocument *Document, pagerange string) error
```

**Parameters**: 
  * **anotherdocument** - reference to PDF-document instance
  * **pagerange** - string that specifies which pages to append. Supports individual pages, ranges, and open-ended intervals. For example: "1,3,5", "2-4", "-3", "4-", or "-" for all pages

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) membuka PDF-dokumen dengan nama file
	pdf, err := asposepdf.Open("sample1page.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf.Close()
	// Open(filename string) membuka PDF-document lain dengan nama file
	anotherpdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer anotherpdf.Close()
	// AppendPages(anotherdocument *Document, pagerange string) menambahkan halaman tertentu dari PDF-document lain.
	err = pdf.AppendPages(anotherpdf, "1,3")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
	err = pdf.SaveAs("sample_AppendPages.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
