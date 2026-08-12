---
title: "MergeDocuments"
second_title: "Aspose.PDF for Go via C++"
description: "Sağlanan PDF-dökümanları birleştirerek yeni bir PDF-dökümanı oluştur."
type: docs
url: /tr/go-cpp/core/mergedocuments/
---

_Sağlanan PDF-belgelerini birleştirerek yeni bir PDF-belgesi oluştur._

```go
func MergeDocuments(documents []*Document) (*Document, error)
```

**Parameters**: 
  * **documents** - slice of PDF-documents to be merged

**Return**: 
  * **\*Document** - new PDF-document containing all pages from the provided PDF-documents
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// New yeni bir PDF belgesi oluşturur
	pdf1, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf1.Close()
	err = pdf1.PageAdd()
	if err != nil {
		log.Fatal(err)
	}
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf2, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf2.Close()
	// MergeDocuments(documents []*Document) sağlanan belgeleri birleştirerek yeni bir PDF-belgesi oluşturur.
	pdf_merged, err := asposepdf.MergeDocuments([]*asposepdf.Document{pdf1, pdf2})
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf_merged.Close()
	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf_merged.SaveAs("sample_MergeDocuments.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
