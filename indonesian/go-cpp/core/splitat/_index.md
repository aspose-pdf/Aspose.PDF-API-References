---
title: "SplitAt"
second_title: "Aspose.PDF untuk Go via C++"
description: "Bagi dokumen PDF saat ini menjadi dua dokumen PDF baru."
type: docs
url: /id/go-cpp/core/splitat/
---

_Membagi PDF-document saat ini menjadi dua PDF-document baru._

```go
func (document *Document) SplitAt(page int) (*Document, *Document, error)
```

**Parameters**: 
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

	// SplitAt(page int) membagi PDF-document saat ini menjadi dua PDF-document baru.
	left, right, err := pdf_split.SplitAt(2)
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-document yang dihasilkan.
	defer left.Close()
	defer right.Close()

	// Simpan setiap bagian sebagai file terpisah
	err = left.SaveAs("sample_SplitAt_left.pdf")
	if err != nil {
		log.Fatal(err)
	}
	err = right.SaveAs("sample_SplitAt_right.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
