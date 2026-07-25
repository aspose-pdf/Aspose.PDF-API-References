---
title: "SaveDocXEnhanced"
second_title: "Aspose.PDF für Go über C++"
description: "Konvertieren und speichern Sie das zuvor geöffnete PDF-Dokument als DocX-Dokument mit erweitertem Erkennungsmodus (vollständig editierbare Tabellen und Absätze)."
type: docs
url: /de/go-cpp/convert/savedocxenhanced/
---

_Konvertieren und das zuvor geöffnete PDF-document als DocX-document mit Enhanced Recognition Mode (vollständig editierbare Tabellen und Absätze) speichern._

```go
func (document *Document) SaveDocXEnhanced(filename string) error
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
	// SaveDocX(filename string) speichert das zuvor geöffnete PDF-document als Enhanced Recognition Mode DocX-document mit Dateiname
	err = pdf.SaveDocXEnhanced("sampleEnhanced.docx")
	if err != nil {
		log.Fatal(err)
	}
}
```
