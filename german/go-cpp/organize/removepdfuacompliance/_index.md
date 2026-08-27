---
title: "RemovePdfUaCompliance"
second_title: "Aspose.PDF für Go über C++"
description: "PDF/UA-Konformität aus einem PDF-Dokument entfernen."
type: docs
url: /de/go-cpp/organize/removepdfuacompliance/
---

_PDF/UA-Konformität aus einem PDF-Dokument entfernen._

```go
func (document *Document) RemovePdfUaCompliance() error
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
	// RemovePdfUaCompliance() entfernt PDF/UA-Konformität aus PDF-Dokument
	err = pdf.RemovePdfUaCompliance()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_RemovePdfUaCompliance.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
