---
title: "Adicionar"
second_title: "Aspose.PDF para Go via C++"
description: "Anexar páginas de outro documento PDF."
type: docs
url: /pt/go-cpp/core/append/
---

_Anexa páginas de outro PDF-document._

```go
func (document *Document) Append(anotherdocument *Document) error
```

**Parameters**: 
  * **anotherdocument** - reference to PDF-document instance

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {

	// Open(filename string) abre um documento PDF com o nome de arquivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}

	// Close() libera os recursos alocados para o documento PDF
	defer pdf.Close()

	// Open(filename string) abre outro PDF-document com o nome de arquivo
	anotherpdf, err := asposepdf.Open("sample1page.pdf")
	if err != nil {
		log.Fatal(err)
	}

	// Close() libera os recursos alocados para o documento PDF
	defer anotherpdf.Close()

	// Append(anotherdocument *Document) anexa páginas de outro PDF-document.
	err = pdf.Append(anotherpdf)
	if err != nil {
		log.Fatal(err)
	}

	// SaveAs(filename string) salva o PDF-document aberto anteriormente com um novo nome de arquivo
	err = pdf.SaveAs("sample_Append.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
