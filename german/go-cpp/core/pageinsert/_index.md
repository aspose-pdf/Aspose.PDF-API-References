---
title: "PageInsert"
second_title: "Aspose.PDF für Go über C++"
description: "Neue Seite an der angegebenen Position im PDF-Dokument einfügen."
type: docs
url: /de/go-cpp/core/pageinsert/
---

_Fügt eine neue Seite an der angegebenen Position im PDF-Dokument ein._

```go
func (document *Document) PageInsert(num int32) error
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
	// PageInsert(num int32) fügt eine neue Seite an der angegebenen Position im PDF-Dokument ein
	err = pdf.PageInsert(1)
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
