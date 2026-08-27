---
title: "ExtractText"
second_title: "Aspose.PDF para Go vía C++"
description: "Devolver el contenido del documento PDF como texto plano."
type: docs
url: /es/go-cpp/core/extracttext/
---

_Devuelve el contenido del documento PDF como texto sin formato._

```go
func (document *Document) ExtractText() (string, error)
```

**Parameters**: 

**Return**: 
  * **string** - PDF-document contents as plain text
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// ExtractText() devuelve el contenido del documento PDF como texto sin formato
	txt, err := pdf.ExtractText()
	if err != nil {
		log.Fatal(err)
	}
	// Imprimir
	fmt.Println("Extracted text:\n", txt)
}
```
