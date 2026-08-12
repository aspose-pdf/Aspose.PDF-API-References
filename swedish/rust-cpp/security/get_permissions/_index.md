---
title: "get_permissions"
second_title: "Aspose.PDF för Rust via C++"
description: "Hämta aktuella behörigheter för PDF-dokument."
type: docs
url: /sv/rust-cpp/security/get_permissions/
---

_Hämta aktuella behörigheter för PDF-dokumentet._

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
    // Öppna ett lösenordsskyddat PDF-dokument
    let pdf = Document::open_with_password("sample_with_permissions.pdf", "ownerpass")?;

    // Hämta aktuella behörigheter för PDF-dokumentet
    let permissions: Permissions = pdf.get_permissions()?;

    // Skriv ut behörigheter
    println!("Permissions: {}", permissions);

    Ok(())
}

```