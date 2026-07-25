---
title: "SaveNUp"
second_title: "Aspose.PDF für Go über C++"
description: "Konvertieren und speichern Sie das zuvor geöffnete PDF-Dokument als N-Up-PDF-Dokument."
type: docs
url: /de/go-cpp/convert/savenup/
---

_Konvertieren und speichern Sie das zuvor geöffnete PDF-Dokument als N-Up PDF-Dokument._

```go
func (document *Document) SaveNUp(filename string, columns int32, rows int32) error
```

**Parameters**: 
  * **filename** - new filename
  * **columns** - number of columns
  * **rows** - number of rows

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
	// SaveNUp(filename string, columns int32, rows int32) speichert das zuvor geöffnete PDF-Dokument als N-Up PDF-Dokument mit Dateinamen
	err = pdf.SaveNUp("sample_NUp.pdf", 2, 2)
	if err != nil {
		log.Fatal(err)
	}
}
```
