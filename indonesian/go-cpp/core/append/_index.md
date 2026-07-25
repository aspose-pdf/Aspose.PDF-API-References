---
title: "Append"
second_title: "Aspose.PDF untuk Go via C++"
description: "Tambahkan halaman dari dokumen PDF lain."
type: docs
url: /id/go-cpp/core/append/
---

_Tambahkan halaman dari PDF-document lain._

```go
func (document *Document) Append(anotherdocument *Document) error
```

**Parameters**: 
  * **anotherdocument** - reference to PDF-document instance

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

	// Open(filename string) membuka PDF-document lain dengan nama file
	anotherpdf, err := asposepdf.Open("sample1page.pdf")
	if err != nil {
		log.Fatal(err)
	}

	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer anotherpdf.Close()

	// Append(anotherdocument *Document) menambahkan halaman dari PDF-document lain.
	err = pdf.Append(anotherpdf)
	if err != nil {
		log.Fatal(err)
	}

	// SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
	err = pdf.SaveAs("sample_Append.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
