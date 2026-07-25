---
title: "SplitDocument"
second_title: "Aspose.PDF für Go über C++"
description: "Mehrere neue PDF-Dokumente erstellen, indem Seiten aus dem Quell-PDF-Dokument extrahiert werden."
type: docs
url: /de/go-cpp/core/splitdocument/
---

_Erstellt mehrere neue PDF-Dokumente, indem Seiten aus dem Quell-PDF-Dokument extrahiert werden._

```go
func SplitDocument(document *Document, pagerange string) ([]*Document, error)
```

**Parameters**: 
  * **document** - pointer to document
  * **pagerange** - string that defines how to split the PDF-document. Each segment, separated by `;`, specifies the page range for a separate output PDF document. The page range syntax supports individual pages, ranges, and open-ended intervals. For example: "1,3,5;7-10", "-3;4-", or "1;2-3;5-"

**Return**: 
  * **[]\*Document** - slice of new PDF-documents, each containing the pages defined by a corresponding segment of the specified page range
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"fmt"
	"log"
	"github.com/aspose-pdf/aspose-pdf-go-cpp"
)

func main() {
	// Open(filename string) öffnet ein PDF-document mit Dateiname
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf_split.Close()

	// SplitDocument(document *Document, pagerange string) erstellt mehrere neue PDF-Dokumente
	pdfs, err := asposepdf.SplitDocument(pdf_split, "1-2;3;4-")
	if err != nil {
		log.Fatal(err)
	}

	// Speichert jedes aufgeteilte PDF-Dokument als separate Datei
	for i, pdf := range pdfs {
		defer pdf.Close()
		filename := fmt.Sprintf("sample_SplitDocument_part%d.pdf", i+1)
		// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
		err := pdf.SaveAs(filename)
		if err != nil {
			log.Fatal(err)
		}
	}
}
```
