---
title: "PageAddTextFooter"
second_title: "Aspose.PDF für Go über C++"
description: "Text in Seitenfußzeile hinzufügen."
type: docs
url: /de/go-cpp/organize/pageaddtextfooter/
---

_Fügt Text in die Fußzeile der Seite ein._

```go
func (document *Document) PageAddTextFooter(num int32, footer string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **footer** - pages footer

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
	// PageAddTextFooter(num int32, footer string) fügt Text in die Fußzeile der Seite ein
	err = pdf.PageAddTextFooter(1, "Footer")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_PageAddTextFooter.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
