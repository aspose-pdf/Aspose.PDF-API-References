---
title: "RemoveSigns"
second_title: "Aspose.PDF für Go über C++"
description: "Signaturen aus dem PDF-Dokument entfernen."
type: docs
url: /de/go-cpp/security/removesigns/
---

_Signaturen aus PDF-Dokument entfernen._

```go
func (document *Document) RemoveSigns(filename string) error
```

**Parameters**: 
  * **filename** - new filename, without signs

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) öffnet ein PDF-document mit Dateiname
	pdf, err := asposepdf.Open("sample_with_sign.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf.Close()
	// RemoveSigns(filename string) entfernt Signaturen aus PDF-Dokument
	err = pdf.RemoveSigns("sample_RemoveSigns.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
