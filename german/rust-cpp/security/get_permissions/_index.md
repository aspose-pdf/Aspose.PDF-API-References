---
title: "get_permissions"
second_title: "Aspose.PDF für Rust über C++"
description: "Erhalte die aktuellen Berechtigungen des PDF-Dokuments."
type: docs
url: /de/rust-cpp/security/get_permissions/
---

_Abrufen der aktuellen Berechtigungen des PDF-Dokuments._

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
    // Öffnen Sie ein passwortgeschütztes PDF-Dokument
    let pdf = Document::open_with_password("sample_with_permissions.pdf", "ownerpass")?;

    // Abrufen der aktuellen Berechtigungen des PDF-Dokuments
    let permissions: Permissions = pdf.get_permissions()?;

    // Berechtigungen drucken
    println!("Permissions: {}", permissions);

    Ok(())
}

```