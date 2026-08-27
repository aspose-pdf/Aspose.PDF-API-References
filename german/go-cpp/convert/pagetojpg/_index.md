---
title: "PageToJpg"
second_title: "Aspose.PDF für Go über C++"
description: "Konvertieren und speichern Sie die angegebene Seite als Jpg-Bild."
type: docs
url: /de/go-cpp/convert/pagetojpg/
---

_Konvertiere und speichere die angegebene Seite als Jpg-Bild._

```go
func (document *Document) PageToJpg(num int32, resolution_dpi int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **resolution_dpi** - resolution in DPI of the resulting file
  * **filename** - new filename

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
	// PageToJpg(num int32, resolution_dpi int32, filename string) speichert die angegebene Seite als Jpg-Bilddatei
	err = pdf.PageToJpg(1, 100, "sample_page1.jpg")
	if err != nil {
		log.Fatal(err)
	}
}
```
