---
title: "PageCount"
second_title: "Aspose.PDF para Go via C++"
description: "Retorne a contagem de páginas no documento PDF."
type: docs
url: /pt/go-cpp/core/pagecount/
---

_Retorna a contagem de páginas no PDF-document._

```go
func (document *Document) PageCount() (int32, error)
```

**Parameters**: 

**Return**: 
  * **int32** - page count of the PDF-document
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) abre um documento PDF com o nome de arquivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera os recursos alocados para o documento PDF
	defer pdf.Close()
	// PageCount() retorna a contagem de páginas no PDF-document
	count, err := pdf.PageCount()
	if err != nil {
		log.Fatal(err)
	}
	// Imprimir
	fmt.Println("Count:", count)
}
```
