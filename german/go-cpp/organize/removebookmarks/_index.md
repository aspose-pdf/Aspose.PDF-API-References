---
title: "RemoveBookmarks"
second_title: "Aspose.PDF für Go über C++"
description: "Lesezeichen aus dem PDF-Dokument entfernen."
type: docs
url: /de/go-cpp/organize/removebookmarks/
---

_Lesezeichen aus dem PDF-Dokument entfernen._

```go
func (document *Document) RemoveBookmarks() error
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
	// RemoveBookmarks() entfernt Lesezeichen aus dem PDF-Dokument
	err = pdf.RemoveBookmarks()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_RemoveBookmarks.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
