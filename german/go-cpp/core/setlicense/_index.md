---
title: "SetLicense"
second_title: "Aspose.PDF für Go über C++"
description: "Lizenz mit Dateinamen festlegen."
type: docs
url: /de/go-cpp/core/setlicense/
---

_Setzt die Lizenz mit Dateinamen._

```go
func (document *Document) SetLicense(filename string) error
```

**Parameters**: 
  * **filename** - full name of the license file

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
	// SetLicense(filename string) lizenziert mit Dateinamen
	err = pdf.SetLicense("Aspose.PDF.GoViaCPP.lic")
	if err != nil {
		log.Fatal(err)
	}
	// Arbeiten mit PDF-Dokument
	// ...
}
```
