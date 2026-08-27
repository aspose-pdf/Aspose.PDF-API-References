---
title: "PageCharacterCount"
second_title: "Aspose.PDF für Go über C++"
description: "Zeichenanzahl auf der angegebenen Seite im PDF-Dokument zurückgeben."
type: docs
url: /de/go-cpp/core/pagecharactercount/
---

_Gibt die Zeichenanzahl auf der angegebenen Seite im PDF-Dokument zurück._

```go
func (document *Document) PageCharacterCount(num int32) (int32, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **int32** - character count on the page
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
	// PageCharacterCount(num int32) gibt die Zeichenanzahl auf der angegebenen Seite im PDF-Dokument zurück.
	page_character_count, err := pdf.PageCharacterCount(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Character count on the first page:", page_character_count)
}
```
