---
title: "SplitAt"
second_title: "Aspose.PDF for Go via C++"
description: "Mevcut PDF-dökümanını iki yeni PDF-dökümanına böl."
type: docs
url: /tr/go-cpp/core/splitat/
---

_Mevcut PDF-dokümanını iki yeni PDF-dokümanına böl._

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
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf_split.Close()

	// SplitAt(page int) mevcut PDF-dokümanını iki yeni PDF-dokümanına böler.
	left, right, err := pdf_split.SplitAt(2)
	if err != nil {
		log.Fatal(err)
	}
	// Close() sonuçlanan PDF-dokümanları için tahsis edilen kaynakları serbest bırakır
	defer left.Close()
	defer right.Close()

	// Her bölümü ayrı bir dosya olarak kaydet
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
