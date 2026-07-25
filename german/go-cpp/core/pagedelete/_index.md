---
title: "PageDelete"
second_title: "Aspose.PDF für Go über C++"
description: "Angegebene Seite im PDF-Dokument löschen."
type: docs
url: /de/go-cpp/core/pagedelete/
---

_Löscht die angegebene Seite im PDF-Dokument._

```go
func (document *Document) PageDelete(num int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document

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
	// PageDelete(num int32) löscht die angegebene Seite im PDF-Dokument
	err = pdf.PageDelete(1)
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
