---
title: "PageToSvg"
second_title: "Aspose.PDF für Go über C++"
description: "Konvertieren und speichern Sie die angegebene Seite als Svg-Bild."
type: docs
url: /de/go-cpp/convert/pagetosvg/
---

_Konvertieren und die angegebene Seite als Svg-image speichern._

```go
func (document *Document) PageToSvg(num int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
	// PageToSvg(num int32, filename string) speichert die angegebene Seite als Svg-Bilddatei
	err = pdf.PageToSvg(1, "sample_page1.svg")
	if err != nil {
		log.Fatal(err)
	}
}
```
