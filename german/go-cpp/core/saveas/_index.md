---
title: "SaveAs"
second_title: "Aspose.PDF für Go über C++"
description: "Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern."
type: docs
url: /de/go-cpp/core/saveas/
---

_Speichern Sie das zuvor geöffnete PDF-Dokument mit neuem Dateinamen._

```go
func (document *Document) SaveAs(filename string) error
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
