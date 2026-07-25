---
title: "Append"
second_title: "Aspose.PDF für Go über C++"
description: "Seiten aus einem anderen PDF-Dokument anhängen."
type: docs
url: /de/go-cpp/core/append/
---

_Fügt Seiten aus einem anderen PDF-Dokument hinzu._

```go
func (document *Document) Append(anotherdocument *Document) error
```

**Parameters**: 
  * **anotherdocument** - reference to PDF-document instance

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {

	// Open(filename string) öffnet ein PDF-document mit Dateiname
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}

	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf.Close()

	// Open(filename string) öffnet ein anderes PDF-Dokument mit dem Dateinamen
	anotherpdf, err := asposepdf.Open("sample1page.pdf")
	if err != nil {
		log.Fatal(err)
	}

	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer anotherpdf.Close()

	// Append(anotherdocument *Document) fügt Seiten aus einem anderen PDF-Dokument hinzu.
	err = pdf.Append(anotherpdf)
	if err != nil {
		log.Fatal(err)
	}

	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_Append.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
