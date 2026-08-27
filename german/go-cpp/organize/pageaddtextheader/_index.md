---
title: "PageAddTextHeader"
second_title: "Aspose.PDF für Go über C++"
description: "Text in Seitenkopfzeile hinzufügen."
type: docs
url: /de/go-cpp/organize/pageaddtextheader/
---

_Text in der Seitenkopfzeile hinzufügen._

```go
func (document *Document) PageAddTextHeader(num int32, header string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
	// PageAddTextHeader(num int32, header string) fügt Text in der Seitenkopfzeile hinzu
	err = pdf.PageAddTextHeader(1, "Header")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_PageAddTextHeader.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
