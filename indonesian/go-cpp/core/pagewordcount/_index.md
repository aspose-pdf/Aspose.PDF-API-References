---
title: "PageWordCount"
second_title: "Aspose.PDF untuk Go via C++"
description: "Kembalikan jumlah kata pada halaman yang ditentukan dalam PDF-dokumen."
type: docs
url: /id/go-cpp/core/pagewordcount/
---

_Kembalikan jumlah kata pada halaman yang ditentukan dalam dokumen PDF._

```go
func (document *Document) PageWordCount(num int32) (int32, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **int32** - word count on the page
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
	// PageWordCount(num int32) mengembalikan jumlah kata pada halaman yang ditentukan dalam dokumen PDF.
	page_word_count, err := pdf.PageWordCount(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Word count on the first page:", page_word_count)
}
```
