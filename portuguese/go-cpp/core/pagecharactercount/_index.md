---
title: "PageCharacterCount"
second_title: "Aspose.PDF para Go via C++"
description: "Retorne a contagem de caracteres na página especificada do documento PDF."
type: docs
url: /pt/go-cpp/core/pagecharactercount/
---

_Retorna a contagem de caracteres na página especificada do PDF-document._

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
	// Open(filename string) abre um documento PDF com o nome de arquivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera os recursos alocados para o documento PDF
	defer pdf.Close()
	// PageCharacterCount(num int32) retorna a contagem de caracteres na página especificada do PDF-document.
	page_character_count, err := pdf.PageCharacterCount(1)
	if err != nil {
		log.Fatal(err)
	}
	// Imprimir
	fmt.Println("Character count on the first page:", page_character_count)
}
```
