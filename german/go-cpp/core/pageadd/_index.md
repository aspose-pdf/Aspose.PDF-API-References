---
title: "PageAdd"
second_title: "Aspose.PDF für Go über C++"
description: "Neue Seite zum PDF-Dokument hinzufügen."
type: docs
url: /de/go-cpp/core/pageadd/
---

_Fügt eine neue Seite im PDF-Dokument hinzu._

```go
func (document *Document) PageAdd() error
```

**Parameters**: 

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
	// PageAdd() fügt eine neue Seite im PDF-Dokument hinzu
	err = pdf.PageAdd()
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
