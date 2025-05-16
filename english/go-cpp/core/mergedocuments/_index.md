---
title: "MergeDocuments"
second_title: Aspose.PDF for Go via C++
description: "Create a new PDF-document by merging the provided PDF-documents."
type: docs
url: /go-cpp/core/mergedocuments/
---

_Create a new PDF-document by merging the provided PDF-documents._

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
	// New creates a new PDF-document
	pdf1, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf1.Close()
	err = pdf1.PageAdd()
	if err != nil {
		log.Fatal(err)
	}
	// Open(filename string) opens a PDF-document with filename
	pdf2, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf2.Close()
	// MergeDocuments(documents []*Document) creates a new PDF-document by merging the provided documents.
	pdf_merged, err := asposepdf.MergeDocuments([]*asposepdf.Document{pdf1, pdf2})
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf_merged.Close()
	// SaveAs(filename string) saves previously opened PDF-document with new filename
	err = pdf_merged.SaveAs("sample_MergeDocuments.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
