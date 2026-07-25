---
title: "SetPermissions"
second_title: "Aspose.PDF para Go vía C++"
description: "Establecer permisos para el documento PDF."
type: docs
url: /es/go-cpp/security/setpermissions/
---

_Establecer permisos para PDF-document._

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
	// New crea un nuevo PDF-documento
	pdf, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()

	// SetPermissions(userPassword, ownerPassword, permissions) establece permisos para PDF-document
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
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_with_permissions.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
