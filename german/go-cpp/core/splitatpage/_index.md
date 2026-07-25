---
title: "SplitAtPage"
second_title: "Aspose.PDF für Go über C++"
description: "Das PDF-Dokument in zwei neue PDF-Dokumente aufteilen."
type: docs
url: /de/go-cpp/core/splitatpage/
---

_Teilt das PDF-Dokument in zwei neue PDF-Dokumente._

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
	// Open(filename string) öffnet ein PDF-document mit Dateiname
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf_split.Close()

	// SplitAtPage(document *Document, page int) erstellt zwei neue PDF-Dokumente
	left, right, err := asposepdf.SplitAtPage(pdf_split, 2)
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt die zugewiesenen Ressourcen für die resultierenden PDF-Dokumente frei
	defer left.Close()
	defer right.Close()

	// Speichere jeden Teil als separate Datei
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
