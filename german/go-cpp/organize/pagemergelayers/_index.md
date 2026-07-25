---
title: "PageMergeLayers"
second_title: "Aspose.PDF für Go über C++"
description: "Alle Ebenen auf der Seite zu einer einzigen Ebene mit dem angegebenen neuen Ebenennamen zusammenführen."
type: docs
url: /de/go-cpp/organize/pagemergelayers/
---

_Führt alle Ebenen auf der Seite zu einer einzigen Ebene mit dem angegebenen neuen Ebenennamen zusammen._

```go
func (document *Document) PageMergeLayers(num int32, newLayerName string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **newLayerName** - name of the new layer after merging

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
	// PageMergeLayers(num int32, newLayerName string) führt alle Ebenen auf der Seite zu einer einzigen Ebene mit dem angegebenen neuen Ebenennamen zusammen
	err = pdf.PageMergeLayers(1, "newLayerName")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_PageMergeLayers.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
