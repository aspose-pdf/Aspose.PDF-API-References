---
title: "SaveTeX"
second_title: "Aspose.PDF para Go via C++"
description: "Converter e salvar o documento PDF aberto anteriormente como documento TeX."
type: docs
url: /pt/go-cpp/convert/savetex/
---

_Converter e salvar o PDF-document aberto anteriormente como TeX-document._

```go
func (document *Document) SaveTeX(filename string) error
```

**Parameters**: 
  * **filename** - new filename

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
	// SaveTeX(filename string) salva o PDF-document aberto anteriormente como TeX-document com nome de arquivo
	err = pdf.SaveTeX("sample.tex")
	if err != nil {
		log.Fatal(err)
	}
}
```
