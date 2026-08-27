---
title: "ClearMetaInfo"
second_title: "Aspose.PDF für Go über C++"
description: "Löscht alle Metainformationswerte des PDF-Dokuments."
type: docs
url: /de/go-cpp/core/clearmetainfo/
---

_Löscht alle Metainformationswerte des PDF-Dokuments._

```go
func (document *Document) ClearMetaInfo() error
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
	// ClearMetaInfo() löscht alle Metainformationswerte des PDF-Dokuments
	err = pdf.ClearMetaInfo()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_ClearMetaInfo.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
