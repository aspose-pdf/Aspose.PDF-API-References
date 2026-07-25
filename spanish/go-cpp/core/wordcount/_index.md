---
title: "WordCount"
second_title: "Aspose.PDF para Go vía C++"
description: "Devolver el recuento de palabras en el documento PDF."
type: docs
url: /es/go-cpp/core/wordcount/
---

_Devuelve el recuento de palabras en el documento PDF._

```go
func (document *Document) WordCount() (int32, error)
```

**Parameters**: 

**Return**: 
  * **int32** - word count of the PDF-document
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
	// WordCount() devuelve el recuento de palabras en el documento PDF
	word_count, err := pdf.WordCount()
	if err != nil {
		log.Fatal(err)
	}
	// Imprimir
	fmt.Println("Word count:", word_count)
}
```
