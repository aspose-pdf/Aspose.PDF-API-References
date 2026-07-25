---
title: "Open"
second_title: "Aspose.PDF für Go über C++"
description: "Ein PDF-Dokument mit Dateinamen öffnen."
type: docs
url: /de/go-cpp/core/open/
---

_Öffnet ein PDF-Dokument mit Dateinamen._

```go
func Open(filename string) (*Document, error)
```

**Parameters**: 
  * **\*Document** - pointer to document
  * **filename** - full file name of the PDF-document

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
	// Save() speichert das zuvor geöffnete PDF-Dokument
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
