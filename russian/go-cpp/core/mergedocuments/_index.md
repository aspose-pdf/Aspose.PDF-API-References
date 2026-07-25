---
title: "MergeDocuments"
second_title: "Aspose.PDF для Go через C++"
description: "Создать новый PDF-document, объединив предоставленные PDF-documents."
type: docs
url: /ru/go-cpp/core/mergedocuments/
---

_Создать новый PDF-документ, объединяя предоставленные PDF-документы._

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
	// New создает новый PDF-документ
	pdf1, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf1.Close()
	err = pdf1.PageAdd()
	if err != nil {
		log.Fatal(err)
	}
	// Open(filename string) открывает PDF-документ с именем файла
	pdf2, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf2.Close()
	// MergeDocuments(documents []*Document) создает новый PDF-документ, объединяя предоставленные документы.
	pdf_merged, err := asposepdf.MergeDocuments([]*asposepdf.Document{pdf1, pdf2})
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf_merged.Close()
	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf_merged.SaveAs("sample_MergeDocuments.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
