---
title: "PageWordCount"
second_title: "Aspose.PDF para Go vía C++"
description: "Devolver el recuento de palabras en la página especificada del documento PDF."
type: docs
url: /es/go-cpp/core/pagewordcount/
---

_Devuelve el recuento de palabras en la página especificada del documento PDF._

```go
func (document *Document) PageWordCount(num int32) (int32, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **int32** - word count on the page
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
	// PageWordCount(num int32) devuelve el recuento de palabras en la página especificada del documento PDF.
	page_word_count, err := pdf.PageWordCount(1)
	if err != nil {
		log.Fatal(err)
	}
	// Imprimir
	fmt.Println("Word count on the first page:", page_word_count)
}
```
