---
title: "CharacterCount"
second_title: "Aspose.PDF para Go vía C++"
description: "Devolver el recuento de caracteres en el documento PDF."
type: docs
url: /es/go-cpp/core/charactercount/
---

_Devuelve el recuento de caracteres en el PDF-documento._

```go
func (document *Document) CharacterCount() (int32, error)
```

**Parameters**: 

**Return**: 
  * **int32** - character count of the PDF-document
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
	// CharacterCount() devuelve el recuento de caracteres en el PDF-documento
	character_count, err := pdf.CharacterCount()
	if err != nil {
		log.Fatal(err)
	}
	// Imprimir
	fmt.Println("Character count:", character_count)
}
```
