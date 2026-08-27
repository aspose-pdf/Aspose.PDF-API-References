---
title: "ExportXfdf"
second_title: "Aspose.PDF für Go über C++"
description: "Exportieren Sie aus dem zuvor geöffneten PDF-Dokument mit AcroForm in ein XFDF-Dokument."
type: docs
url: /de/go-cpp/convert/exportxfdf/
---

_Exportieren Sie aus dem zuvor geöffneten PDF-Dokument mit AcroForm zu XFDF-Dokument._

```go
func (document *Document) ExportXfdf(filename string) error
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
	// ExportXfdf(filename string) exportiert aus dem zuvor geöffneten PDF-Dokument mit AcroForm zu XFDF-Dokument mit Dateinamen
	err = pdf.ExportXfdf("sample.xfdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
