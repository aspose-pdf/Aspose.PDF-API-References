---
title: "ReplaceText"
second_title: "Aspose.PDF para Go vía C++"
description: "Reemplazar texto en PDF-document."
type: docs
url: /es/go-cpp/organize/replacetext/
---

_Reemplazar texto en un documento PDF._

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
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// ReplaceText(findText, replaceText string) reemplaza texto en un documento PDF
	err = pdf.ReplaceText("PDF", "TXT")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_ReplaceText.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
