---
title: "PageIsBlank"
second_title: "Aspose.PDF untuk Go via C++"
description: "Kembalikan apakah halaman kosong dalam PDF-dokumen."
type: docs
url: /id/go-cpp/core/pageisblank/
---

_Kembalikan apakah halaman kosong dalam dokumen PDF._

```go
func (document *Document) PageIsBlank(num int32) (bool, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **bool** - the page is blank
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) membuka PDF-dokumen dengan nama file
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf.Close()
	// PageIsBlank(num int32) mengembalikan apakah halaman kosong dalam dokumen PDF.
	page_is_blank, err := pdf.PageIsBlank(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("The first page is blank?:", page_is_blank == true)
}
```
