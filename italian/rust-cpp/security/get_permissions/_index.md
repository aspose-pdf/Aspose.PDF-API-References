---
title: "get_permissions"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Ottieni i permessi attuali del PDF-document."
type: docs
url: /it/rust-cpp/security/get_permissions/
---

_Ottieni le autorizzazioni correnti del PDF-document._

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
    // Apri un PDF-document protetto da password
    let pdf = Document::open_with_password("sample_with_permissions.pdf", "ownerpass")?;

    // Ottieni le autorizzazioni correnti del PDF-document
    let permissions: Permissions = pdf.get_permissions()?;

    // Stampa le autorizzazioni
    println!("Permissions: {}", permissions);

    Ok(())
}

```