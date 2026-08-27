---
title: "WordCount"
second_title: "Aspose.PDF para Go via C++"
description: "Retornar a contagem de palavras no documento PDF."
type: docs
url: /pt/go-cpp/core/wordcount/
---

_Retorna a contagem de palavras no PDF-document._

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
	// Open(filename string) abre um documento PDF com o nome de arquivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera os recursos alocados para o documento PDF
	defer pdf.Close()
	// WordCount() retorna a contagem de palavras no PDF-document.
	word_count, err := pdf.WordCount()
	if err != nil {
		log.Fatal(err)
	}
	// Imprimir
	fmt.Println("Word count:", word_count)
}
```
