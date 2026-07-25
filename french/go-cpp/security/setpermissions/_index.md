---
title: "SetPermissions"
second_title: "Aspose.PDF pour Go via C++"
description: "Définir les autorisations pour le PDF-document."
type: docs
url: /fr/go-cpp/security/setpermissions/
---

_Définir les autorisations du document PDF._

```go
func (document *Document) SetPermissions(userPassword string, ownerPassword string, permissions Permissions) error
```

**Parameters**: 
  * **userPassword** - user password
  * **ownerPassword** - owner password
  * **permissions** - bitmask of allowed PDF permissions (combine flags using `|`):
```go
type Permissions int32
const (
    PrintDocument                  Permissions = 1 << 2  // 4
    ModifyContent                  Permissions = 1 << 3  // 8
    ExtractContent                 Permissions = 1 << 4  // 16
    ModifyTextAnnotations          Permissions = 1 << 5  // 32
    FillForm                       Permissions = 1 << 8  // 256
    ExtractContentWithDisabilities Permissions = 1 << 9  // 512
    AssembleDocument               Permissions = 1 << 10 // 1024
    PrintingQuality                Permissions = 1 << 11 // 2048
)
```

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// New crée un nouveau PDF-document
	pdf, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf.Close()

	// SetPermissions(userPassword, ownerPassword, permissions) définit les autorisations du document PDF
	err = pdf.SetPermissions(
		"userpass",
		"ownerpass",
		asposepdf.PrintDocument|
			asposepdf.ModifyContent|
			asposepdf.FillForm,
	)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
	err = pdf.SaveAs("sample_with_permissions.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
