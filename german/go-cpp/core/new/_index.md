---
title: "Neu"
second_title: "Aspose.PDF für Go über C++"
description: "Ein neues PDF-Dokument erstellen."
type: docs
url: /de/go-cpp/core/new/
---

_Erstelle ein neues PDF-Dokument._

```go
func New() (*Document, error)
```

**Parameters**: 

**Return**:
  * **\*Document** - pointer to document
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// New erstellt ein neues PDF-Dokument
	pdf, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf.Close()
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_New_SaveAs.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
