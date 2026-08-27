---
title: "PageCount"
second_title: "Aspose.PDF untuk Go via C++"
description: "Kembalikan jumlah halaman dalam PDF-dokumen."
type: docs
url: /id/go-cpp/core/pagecount/
---

_Kembalikan jumlah halaman dalam PDF-document._

```go
func (document *Document) PageCount() (int32, error)
```

**Parameters**: 

**Return**: 
  * **int32** - page count of the PDF-document
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
	// PageCount() mengembalikan jumlah halaman dalam PDF-document
	count, err := pdf.PageCount()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Count:", count)
}
```
