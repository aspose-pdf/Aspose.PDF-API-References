---
title: "Split"
second_title: "Aspose.PDF for Go via C++"
description: "Mevcut PDF-dökümanından sayfaları çıkararak birden fazla yeni PDF-dökümanı oluştur."
type: docs
url: /tr/go-cpp/core/split/
---

_Mevcut PDF-document'tan sayfalar çıkararak birden fazla yeni PDF-document oluştur._

```go
func (document *Document) Split(pagerange string) ([]*Document, error)
```

**Parameters**: 
  * **pagerange** - string that defines how to split the PDF-document. Each segment, separated by `;`, specifies the page range for a separate output PDF document. The page range syntax supports individual pages, ranges, and open-ended intervals. For example: "1,3,5;7-10", "-3;4-", or "1;2-3;5-"

**Return**: 
  * **[]\*Document** - slice of new PDF-documents, each containing the pages defined by a corresponding segment of the specified page range
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"fmt"
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

	// Split(pagerange string) mevcut PDF-document'tan sayfalar çıkararak birden fazla yeni PDF-document oluşturur
	pdfs, err := pdf_split.Split("1-2;3;4-")
	if err != nil {
		log.Fatal(err)
	}

	// Her bölünmüş PDF-document'i ayrı bir dosya olarak kaydet
	for i, pdf := range pdfs {
		defer pdf.Close()
		filename := fmt.Sprintf("sample_Split_part%d.pdf", i+1)
		// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
		err := pdf.SaveAs(filename)
		if err != nil {
			log.Fatal(err)
		}
	}
}
```
