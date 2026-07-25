---
title: "SplitAtPage"
second_title: "Aspose.PDF para Go via C++"
description: "Dividir o documento PDF em dois novos documentos PDF."
type: docs
url: /pt/go-cpp/core/splitatpage/
---

_Divide o documento PDF em dois novos documentos PDF._

```go
func SplitAtPage(document *Document, page int) (*Document, *Document, error)
```

**Parameters**: 
  * **document** - pointer to document
  * **page** - page number at which to split the PDF-document. Pages up to and including this page go into the first PDF-document

**Return**: 
  * **\*Document** - new PDF-document containing pages 1 to page (inclusive)
  * **\*Document** - new PDF-document containing pages from page + 1 to the end
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"github.com/aspose-pdf/aspose-pdf-go-cpp"
	"log"
)

func main() {
	// Open(filename string) abre um documento PDF com o nome de arquivo
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera os recursos alocados para o documento PDF
	defer pdf_split.Close()

	// SplitAtPage(document *Document, page int) cria dois novos documentos PDF
	left, right, err := asposepdf.SplitAtPage(pdf_split, 2)
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera os recursos alocados para os PDF-documents resultantes
	defer left.Close()
	defer right.Close()

	// Salve cada parte como um arquivo separado
	err = left.SaveAs("sample_SplitAtPage_left.pdf")
	if err != nil {
		log.Fatal(err)
	}
	err = right.SaveAs("sample_SplitAtPage_right.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
