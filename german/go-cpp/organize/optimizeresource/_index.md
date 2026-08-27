---
title: "OptimizeResource"
second_title: "Aspose.PDF für Go über C++"
description: "Ressourcen des PDF-Dokuments optimieren."
type: docs
url: /de/go-cpp/organize/optimizeresource/
---

_Optimiere Ressourcen eines PDF-Dokuments._

```go
func (document *Document) OptimizeResource() error
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
	// OptimizeResource() optimiert Ressourcen eines PDF-Dokuments
	err = pdf.OptimizeResource()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_OptimizeResource.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
