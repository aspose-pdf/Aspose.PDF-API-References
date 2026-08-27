---
title: "SplitAtPage"
second_title: "Aspose.PDF untuk Go via C++"
description: "Bagi dokumen PDF menjadi dua dokumen PDF baru."
type: docs
url: /id/go-cpp/core/splitatpage/
---

_Pisahkan dokumen PDF menjadi dua dokumen PDF baru._

```go
func SplitAtPage(document *Document, page int) (*Document, *Document, error)
```

**Parameters**: 
  * **document** - pointer to document
  * **page** - page number at which to split the PDF-document. Pages up to and including this page go into the first PDF-document

**Return**: 
  * **\*Document** - new PDF-document containing pages 1 to page (inclusive)
  * **\*Document** - new PDF-document containing pages from page + 1 to the end
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"github.com/aspose-pdf/aspose-pdf-go-cpp"
	"log"
)

func main() {
	// Open(filename string) membuka PDF-dokumen dengan nama file
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf_split.Close()

	// SplitAtPage(document *Document, page int) membuat dua dokumen PDF baru
	left, right, err := asposepdf.SplitAtPage(pdf_split, 2)
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-document yang dihasilkan.
	defer left.Close()
	defer right.Close()

	// Simpan setiap bagian sebagai file terpisah
	err = left.SaveAs("sample_SplitAtPage_left.pdf")
	if err != nil {
		log.Fatal(err)
	}
	err = right.SaveAs("sample_SplitAtPage_right.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
