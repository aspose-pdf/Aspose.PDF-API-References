---
title: "AddTextHeader"
second_title: "Aspose.PDF für Go über C++"
description: "Text in der Kopfzeile eines PDF-Dokuments hinzufügen."
type: docs
url: /de/go-cpp/organize/addtextheader/
---

_Text in die Kopfzeile eines PDF-Dokuments hinzufügen._

```go
func (document *Document) AddTextHeader(header string) error
```

**Parameters**: 
  * **header** - pages header

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
	// AddTextHeader(header string) fügt Text in die Kopfzeile eines PDF-Dokuments ein
	err = pdf.AddTextHeader("Header")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_AddTextHeader.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
