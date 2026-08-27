---
title: "ExtractText"
second_title: "Aspose.PDF untuk Go via C++"
description: "Kembalikan isi dokumen PDF sebagai teks biasa."
type: docs
url: /id/go-cpp/core/extracttext/
---

_Kembalikan isi dokumen PDF sebagai teks biasa._

```go
func (document *Document) ExtractText() (string, error)
```

**Parameters**: 

**Return**: 
  * **string** - PDF-document contents as plain text
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
	// ExtractText() mengembalikan isi dokumen PDF sebagai teks biasa
	txt, err := pdf.ExtractText()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Extracted text:\n", txt)
}
```
