---
title: "SaveMarkdown"
second_title: "Aspose.PDF para Go vía C++"
description: "Convertir y guardar el PDF-documento previamente abierto como documento Markdown."
type: docs
url: /es/go-cpp/convert/savemarkdown/
---

_Convierte y guarda el PDF-document previamente abierto como documento Markdown._

```go
func (document *Document) SaveMarkdown(filename string) error
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
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// SaveMarkdown(filename string) guarda el PDF-document previamente abierto como documento Markdown con filename
	err = pdf.SaveMarkdown("sample.md")
	if err != nil {
		log.Fatal(err)
	}
}
```
