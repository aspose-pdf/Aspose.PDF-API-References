---
title: "SaveDocXEnhanced"
second_title: "Aspose.PDF para Go via C++"
description: "Converter e salvar o documento PDF aberto anteriormente como documento DocX com Modo de Reconhecimento Avançado (tabelas e parágrafos totalmente editáveis)."
type: docs
url: /pt/go-cpp/convert/savedocxenhanced/
---

_Converta e salve o documento PDF previamente aberto como documento DocX com Modo de Reconhecimento Avançado (tabelas e parágrafos totalmente editáveis)._

```go
func (document *Document) SaveDocXEnhanced(filename string) error
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
	// SaveDocX(filename string) salva o documento PDF previamente aberto como documento DocX em Modo de Reconhecimento Avançado com o nome de arquivo
	err = pdf.SaveDocXEnhanced("sampleEnhanced.docx")
	if err != nil {
		log.Fatal(err)
	}
}
```
