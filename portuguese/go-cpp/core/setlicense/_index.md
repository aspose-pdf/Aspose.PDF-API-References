---
title: "SetLicense"
second_title: "Aspose.PDF para Go via C++"
description: "Definir licença com o nome do arquivo."
type: docs
url: /pt/go-cpp/core/setlicense/
---

_Define a licença com o nome de arquivo._

```go
func (document *Document) SetLicense(filename string) error
```

**Parameters**: 
  * **filename** - full name of the license file

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
	// SetLicense(filename string) licencia com o nome de arquivo
	err = pdf.SetLicense("Aspose.PDF.GoViaCPP.lic")
	if err != nil {
		log.Fatal(err)
	}
	// Trabalhando com PDF-document
	// ...
}
```
