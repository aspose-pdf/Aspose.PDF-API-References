---
title: "PageAddText"
second_title: "Aspose.PDF für Go über C++"
description: "Text auf Seite hinzufügen."
type: docs
url: /de/go-cpp/organize/pageaddtext/
---

_Text auf Seite hinzufügen._

```go
func (document *Document) PageAddText(num int32, addText string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **addText** - added text

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
	// PageAddText(num int32, addText string) fügt Text auf der Seite hinzu
	err = pdf.PageAddText(1, "added text")
	if err != nil {
		log.Fatal(err)
	}
	// Save() speichert das zuvor geöffnete PDF-Dokument
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
