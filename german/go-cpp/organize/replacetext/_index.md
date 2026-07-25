---
title: "ReplaceText"
second_title: "Aspose.PDF für Go über C++"
description: "Text im PDF-Dokument ersetzen."
type: docs
url: /de/go-cpp/organize/replacetext/
---

_Ersetze Text in einem PDF-Dokument._

```go
func (document *Document) ReplaceText(findText, replaceText string) error
```

**Parameters**: 
  * **findText** - text fragment to search
  * **replaceText** - text fragment to replace

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
	// ReplaceText(findText, replaceText string) ersetzt Text in einem PDF-Dokument
	err = pdf.ReplaceText("PDF", "TXT")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_ReplaceText.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
