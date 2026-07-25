---
title: "WordCount"
second_title: "Aspose.PDF untuk Go via C++"
description: "Kembalikan jumlah kata dalam dokumen PDF."
type: docs
url: /id/go-cpp/core/wordcount/
---

_Mengembalikan jumlah kata dalam PDF-document._

```go
func (document *Document) WordCount() (int32, error)
```

**Parameters**: 

**Return**: 
  * **int32** - word count of the PDF-document
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
	// WordCount() mengembalikan jumlah kata dalam PDF-document
	word_count, err := pdf.WordCount()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Word count:", word_count)
}
```
