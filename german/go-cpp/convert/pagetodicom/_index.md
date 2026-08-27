---
title: "PageToDICOM"
second_title: "Aspose.PDF für Go über C++"
description: "Konvertieren und speichern Sie die angegebene Seite als DICOM-Bild."
type: docs
url: /de/go-cpp/convert/pagetodicom/
---

_Konvertieren und die angegebene Seite als DICOM-image speichern._

```go
func (document *Document) PageToDICOM(num int32, resolution_dpi int32, filename string) error
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
	// PageToDICOM(num int32, resolution_dpi int32, filename string) speichert die angegebene Seite als DICOM-image Datei
	err = pdf.PageToDICOM(1, 100, "sample_page1.dcm")
	if err != nil {
		log.Fatal(err)
	}
}
```
