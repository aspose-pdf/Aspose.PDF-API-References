---
title: "PageReplaceText"
second_title: "Aspose.PDF para Go vía C++"
description: "Reemplazar texto en la página."
type: docs
url: /es/go-cpp/organize/pagereplacetext/
---

_Reemplazar texto en la página._

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
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// PageReplaceText(num int32, findText, replaceText string) reemplaza texto en la página
	err = pdf.PageReplaceText(1, "PDF", "TXT")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_page1_ReplaceText.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
