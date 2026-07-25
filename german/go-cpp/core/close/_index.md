---
title: "Close"
second_title: "Aspose.PDF für Go über C++"
description: "Zugewiesene Ressourcen für das PDF-Dokument freigeben."
type: docs
url: /de/go-cpp/core/close/
---

_Gibt die zugewiesenen Ressourcen für das PDF-Dokument frei._

```go
func (document *Document) Close() error
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
