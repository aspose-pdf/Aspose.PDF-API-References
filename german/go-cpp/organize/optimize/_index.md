---
title: "Optimieren"
second_title: "Aspose.PDF für Go über C++"
description: "PDF-Dokumentinhalt optimieren."
type: docs
url: /de/go-cpp/organize/optimize/
---

_Optimieren Sie den Inhalt des PDF-Dokuments._

```go
func (document *Document) Optimize() error
```

**Parameters**: 

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
	// Optimize() optimiert den Inhalt des PDF-Dokuments
	err = pdf.Optimize()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_Optimize.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
