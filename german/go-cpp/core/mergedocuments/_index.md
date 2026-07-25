---
title: "MergeDocuments"
second_title: "Aspose.PDF für Go über C++"
description: "Ein neues PDF-Dokument erstellen, indem die bereitgestellten PDF-Dokumente zusammengeführt werden."
type: docs
url: /de/go-cpp/core/mergedocuments/
---

_Erstelle ein neues PDF-Dokument, indem du die bereitgestellten PDF-Dokumente zusammenführst._

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
	// New erstellt ein neues PDF-Dokument
	pdf1, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf1.Close()
	err = pdf1.PageAdd()
	if err != nil {
		log.Fatal(err)
	}
	// Open(filename string) öffnet ein PDF-document mit Dateiname
	pdf2, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf2.Close()
	// MergeDocuments(documents []*Document) erstellt ein neues PDF-Dokument, indem die bereitgestellten Dokumente zusammengeführt werden.
	pdf_merged, err := asposepdf.MergeDocuments([]*asposepdf.Document{pdf1, pdf2})
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf_merged.Close()
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf_merged.SaveAs("sample_MergeDocuments.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
