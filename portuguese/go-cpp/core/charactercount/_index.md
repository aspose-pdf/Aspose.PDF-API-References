---
title: "CharacterCount"
second_title: "Aspose.PDF para Go via C++"
description: "Retornar a contagem de caracteres no documento PDF."
type: docs
url: /pt/go-cpp/core/charactercount/
---

_Retorna a contagem de caracteres no PDF-document._

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
	// Open(filename string) abre um documento PDF com o nome de arquivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera os recursos alocados para o documento PDF
	defer pdf.Close()
	// CharacterCount() retorna a contagem de caracteres no PDF-document
	character_count, err := pdf.CharacterCount()
	if err != nil {
		log.Fatal(err)
	}
	// Imprimir
	fmt.Println("Character count:", character_count)
}
```
