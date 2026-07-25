---
title: "Split"
second_title: "Aspose.PDF für Go über C++"
description: "Mehrere neue PDF-Dokumente erstellen, indem Seiten aus dem aktuellen PDF-Dokument extrahiert werden."
type: docs
url: /de/go-cpp/core/split/
---

_Erstellt mehrere neue PDF-Dokumente, indem Seiten aus dem aktuellen PDF-Dokument extrahiert werden._

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
	// Open(filename string) öffnet ein PDF-document mit Dateiname
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf_split.Close()

	// Split(pagerange string) erstellt mehrere neue PDF-Dokumente, indem Seiten aus dem aktuellen PDF-Dokument extrahiert werden
	pdfs, err := pdf_split.Split("1-2;3;4-")
	if err != nil {
		log.Fatal(err)
	}

	// Speichert jedes aufgeteilte PDF-Dokument als separate Datei
	for i, pdf := range pdfs {
		defer pdf.Close()
		filename := fmt.Sprintf("sample_Split_part%d.pdf", i+1)
		// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
		err := pdf.SaveAs(filename)
		if err != nil {
			log.Fatal(err)
		}
	}
}
```
