---
title: "SaveDoc"
second_title: "Aspose.PDF für Go über C++"
description: "Konvertieren und speichern Sie das zuvor geöffnete PDF-Dokument als Doc-Dokument."
type: docs
url: /de/go-cpp/convert/savedoc/
---

_Konvertiere und speichere das zuvor geöffnete PDF-Dokument als Doc-Dokument._

```go
func (document *Document) SaveDoc(filename string) error
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
	// SaveDoc(filename string) speichert das zuvor geöffnete PDF-Dokument als Doc-Dokument mit Dateinamen
	err = pdf.SaveDoc("sample.doc")
	if err != nil {
		log.Fatal(err)
	}
}
```
