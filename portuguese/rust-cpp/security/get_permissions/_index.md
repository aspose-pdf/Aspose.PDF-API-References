---
title: "get_permissions"
second_title: "Aspose.PDF para Rust via C++"
description: "Obter permissões atuais do PDF-document."
type: docs
url: /pt/rust-cpp/security/get_permissions/
---

_Obter permissões atuais do documento PDF._

```rust
pub fn get_permissions(&self) -> Result<Permissions, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Permissions)** - the bitmask of permissions, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Permissions};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF protegido por senha
    let pdf = Document::open_with_password("sample_with_permissions.pdf", "ownerpass")?;

    // Obter permissões atuais do documento PDF
    let permissions: Permissions = pdf.get_permissions()?;

    // Imprimir permissões
    println!("Permissions: {}", permissions);

    Ok(())
}

```