---
title: "PageReplaceText"
second_title: "Aspose.PDF für Go über C++"
description: "Text auf Seite ersetzen."
type: docs
url: /de/go-cpp/organize/pagereplacetext/
---

_Text auf der Seite ersetzen._

```go
func (document *Document) PageReplaceText(num int32, findText, replaceText string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
	// PageReplaceText(num int32, findText, replaceText string) ersetzt Text auf der Seite
	err = pdf.PageReplaceText(1, "PDF", "TXT")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_page1_ReplaceText.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
