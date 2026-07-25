---
title: "ExportXml"
second_title: "Aspose.PDF für Go über C++"
description: "Exportieren Sie aus dem zuvor geöffneten PDF-Dokument mit AcroForm in ein XML-Dokument."
type: docs
url: /de/go-cpp/convert/exportxml/
---

_Exportieren aus dem zuvor geöffneten PDF-document mit AcroForm in ein XML-document._

```go
func (document *Document) ExportXml(filename string) error
```

**Parameters**: 
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
	// ExportXml(filename string) exportiert aus dem zuvor geöffneten PDF-document mit AcroForm in ein XML-document mit Dateiname
	err = pdf.ExportXml("sample.xml")
	if err != nil {
		log.Fatal(err)
	}
}
```
