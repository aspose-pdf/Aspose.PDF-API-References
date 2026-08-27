---
title: "PageGrayscale"
second_title: "Aspose.PDF für Go über C++"
description: "Seite in Schwarzweiß konvertieren."
type: docs
url: /de/go-cpp/organize/pagegrayscale/
---

_Konvertiere Seite in Schwarzweiß._

```go
func (document *Document) PageGrayscale(num int32) error
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
	// PageGrayscale(num int32) konvertiert Seite in Schwarzweiß
	err = pdf.PageGrayscale(1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_page1_Grayscale.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
