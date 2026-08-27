---
title: "AddPageNum"
second_title: "Aspose.PDF für Go über C++"
description: "Seitenzahl zu einem PDF-Dokument hinzufügen."
type: docs
url: /de/go-cpp/organize/addpagenum/
---

_Seitenzahl zu einem PDF-Dokument hinzufügen._

```go
func (document *Document) AddPageNum() error
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
	// AddPageNum() fügt Seitenzahl zu einem PDF-Dokument hinzu
	err = pdf.AddPageNum()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_AddPageNum.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
