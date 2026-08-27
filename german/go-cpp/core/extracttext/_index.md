---
title: "ExtractText"
second_title: "Aspose.PDF für Go über C++"
description: "Den Inhalt des PDF-Dokuments als Klartext zurückgeben."
type: docs
url: /de/go-cpp/core/extracttext/
---

_Geben Sie den PDF-Dokumentinhalt als Klartext zurück._

```go
func (document *Document) ExtractText() (string, error)
```

**Parameters**: 

**Return**: 
  * **string** - PDF-document contents as plain text
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) öffnet ein PDF-document mit Dateiname
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf.Close()
	// ExtractText() gibt den PDF-Dokumentinhalt als Klartext zurück
	txt, err := pdf.ExtractText()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Extracted text:\n", txt)
}
```
