---
title: "PageAddPageNum"
second_title: "Aspose.PDF für Go über C++"
description: "Seitennummer auf Seite hinzufügen."
type: docs
url: /de/go-cpp/organize/pageaddpagenum/
---

_Füge Seitenzahl auf Seite hinzu._

```go
func (document *Document) PageAddPageNum(num int32) error
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
	// PageAddPageNum(num int32) fügt die Seitenzahl auf der Seite hinzu
	err = pdf.PageAddPageNum(1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_page1_AddPageNum.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
