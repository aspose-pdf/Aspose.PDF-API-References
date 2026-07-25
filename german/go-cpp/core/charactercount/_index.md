---
title: "CharacterCount"
second_title: "Aspose.PDF für Go über C++"
description: "Zeichenanzahl im PDF-Dokument zurückgeben."
type: docs
url: /de/go-cpp/core/charactercount/
---

_Gibt die Zeichenanzahl im PDF-Dokument zurück._

```go
func (document *Document) CharacterCount() (int32, error)
```

**Parameters**: 

**Return**: 
  * **int32** - character count of the PDF-document
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
	// CharacterCount() gibt die Zeichenanzahl im PDF-Dokument zurück
	character_count, err := pdf.CharacterCount()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Character count:", character_count)
}
```
