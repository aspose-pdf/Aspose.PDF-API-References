---
title: "IsEncrypted"
second_title: "Aspose.PDF para Go via C++"
description: "Obtenha o status de criptografia do documento PDF."
type: docs
url: /pt/go-cpp/security/isencrypted/
---

_Obtenha o status de criptografia do documento PDF._

```go
func (document *Document) IsEncrypted() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is encrypted
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// OpenWithPassword(filename string, password string) abre um documento PDF protegido por senha
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera os recursos alocados para o documento PDF
	defer pdf.Close()
	// IsEncrypted() obtém o status de criptografia do documento PDF
	isEnc, _ := pdf.IsEncrypted()
	if isEnc {
		fmt.Println("IsEncrypted() is true")
	}
}
```
