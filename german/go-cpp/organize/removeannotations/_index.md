---
title: "RemoveAnnotations"
second_title: "Aspose.PDF für Go über C++"
description: "Annotationen aus dem PDF-Dokument entfernen."
type: docs
url: /de/go-cpp/organize/removeannotations/
---

_Entfernt Anmerkungen aus dem PDF-Dokument._

```go
func (document *Document) RemoveAnnotations() error
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
	// RemoveAnnotations() entfernt Anmerkungen aus dem PDF-Dokument
	err = pdf.RemoveAnnotations()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_RemoveAnnotations.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
