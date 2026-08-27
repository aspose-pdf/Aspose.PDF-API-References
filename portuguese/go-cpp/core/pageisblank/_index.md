---
title: "PageIsBlank"
second_title: "Aspose.PDF para Go via C++"
description: "Retorne se a página está em branco no documento PDF."
type: docs
url: /pt/go-cpp/core/pageisblank/
---

_Retorna se a página está em branco no documento PDF._

```go
func (document *Document) PageIsBlank(num int32) (bool, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **bool** - the page is blank
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
	// PageIsBlank(num int32) retorna se a página está em branco no documento PDF.
	page_is_blank, err := pdf.PageIsBlank(1)
	if err != nil {
		log.Fatal(err)
	}
	// Imprimir
	fmt.Println("The first page is blank?:", page_is_blank == true)
}
```
