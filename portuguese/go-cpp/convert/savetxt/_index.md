---
title: "SaveTxt"
second_title: "Aspose.PDF para Go via C++"
description: "Converter e salvar o documento PDF aberto anteriormente como documento Txt."
type: docs
url: /pt/go-cpp/convert/savetxt/
---

_Converte e salva o PDF-documento previamente aberto como Txt-document._

```go
func (document *Document) SaveTxt(filename string) error
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
	// SaveTxt(filename string) salva o PDF-documento previamente aberto como Txt-document com filename
	err = pdf.SaveTxt("sample.txt")
	if err != nil {
		log.Fatal(err)
	}
}
```
