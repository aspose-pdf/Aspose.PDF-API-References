---
title: "Open"
second_title: "Aspose.PDF para Go via C++"
description: "Abrir um documento PDF com o nome do arquivo."
type: docs
url: /pt/go-cpp/core/open/
---

_Abre um PDF-document com o nome de arquivo._

```go
func Open(filename string) (*Document, error)
```

**Parameters**: 
  * **\*Document** - pointer to document
  * **filename** - full file name of the PDF-document

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
	// Save() salva o PDF-document aberto anteriormente
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
