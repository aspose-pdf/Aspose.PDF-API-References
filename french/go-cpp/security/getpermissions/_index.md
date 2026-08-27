---
title: "GetPermissions"
second_title: "Aspose.PDF pour Go via C++"
description: "Obtenir les autorisations du document PDF."
type: docs
url: /fr/go-cpp/security/getpermissions/
---

_Obtenir les autorisations du document PDF._

```go
func (document *Document) GetPermissions() (Permissions, error)
```

**Parameters**: 

**Return**: 
  * **Permissions** - bitmask of PDF permission flags:
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
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import (
	"fmt"
	"log"
	"strings"
)

var permissionNames = map[asposepdf.Permissions]string{
	asposepdf.PrintDocument:                  "Allow printing",
	asposepdf.ModifyContent:                  "Allow modifying content (except forms/annotations)",
	asposepdf.ExtractContent:                 "Allow copying/extracting text and graphics",
	asposepdf.ModifyTextAnnotations:          "Allow adding/modifying text annotations",
	asposepdf.FillForm:                       "Allow filling interactive forms",
	asposepdf.ExtractContentWithDisabilities: "Allow content extraction for accessibility",
	asposepdf.AssembleDocument:               "Allow inserting/rotating/deleting pages or changing structure",
	asposepdf.PrintingQuality:                "Allow high-quality / faithful printing",
}

func PermissionsToString(p asposepdf.Permissions) string {
	var result []string
	for flag, name := range permissionNames {
		if p&flag != 0 {
			result = append(result, name)
		}
	}
	if len(result) == 0 {
		return "None"
	}
	return strings.Join(result, ", ")
}

func main() {
	// OpenWithPassword(filename string, password string) ouvre un PDF-document protégé par mot de passe
	pdf, err := asposepdf.OpenWithPassword("sample_with_permissions.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf.Close()
	// GetPermissions() obtient les autorisations actuelles du document PDF
	permissions, err := pdf.GetPermissions()
	if err != nil {
		log.Fatal(err)
	}
	// Imprimer les autorisations
	fmt.Println("Permissions:", PermissionsToString(permissions))
}
```
