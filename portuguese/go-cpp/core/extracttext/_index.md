---
title: "ExtractText"
second_title: "Aspose.PDF para Go via C++"
description: "Retornar o conteúdo do documento PDF como texto simples."
type: docs
url: /pt/go-cpp/core/extracttext/
---

_Retorna o conteúdo do PDF-document como texto simples._

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
	// Open(filename string) abre um documento PDF com o nome de arquivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera os recursos alocados para o documento PDF
	defer pdf.Close()
	// ExtractText() retorna o conteúdo do PDF-document como texto simples
	txt, err := pdf.ExtractText()
	if err != nil {
		log.Fatal(err)
	}
	// Imprimir
	fmt.Println("Extracted text:\n", txt)
}
```
