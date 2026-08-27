---
title: "PageCharacterCount"
second_title: "Aspose.PDF para Go vía C++"
description: "Devolver el recuento de caracteres en la página especificada del documento PDF."
type: docs
url: /es/go-cpp/core/pagecharactercount/
---

_Devuelve el recuento de caracteres en la página especificada del documento PDF._

```go
func (document *Document) PageCharacterCount(num int32) (int32, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **int32** - character count on the page
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
	// PageCharacterCount(num int32) devuelve el recuento de caracteres en la página especificada del documento PDF.
	page_character_count, err := pdf.PageCharacterCount(1)
	if err != nil {
		log.Fatal(err)
	}
	// Imprimir
	fmt.Println("Character count on the first page:", page_character_count)
}
```
