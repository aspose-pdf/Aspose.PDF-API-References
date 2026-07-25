---
title: "SetMetaInfo"
second_title: "Aspose.PDF para Go via C++"
description: "Define o valor da meta informação do PDF-document."
type: docs
url: /pt/go-cpp/core/setmetainfo/
---

_Define o valor da meta informação do PDF-document._

```go
func (document *Document) SetMetaInfo(key, value string) error
```

**Parameters**: 
  * **key** - key whose value to set
  * **value** - value to be set

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
	// SetMetaInfo(key, value string) define o valor da meta informação do PDF-document
	err = pdf.SetMetaInfo("Author", "Aspose")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) salva o PDF-document aberto anteriormente com um novo nome de arquivo
	err = pdf.SaveAs("sample_SetMetaInfo.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
