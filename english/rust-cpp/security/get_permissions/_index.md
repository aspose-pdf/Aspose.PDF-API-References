---
title: "get_permissions"
second_title: Aspose.PDF for Rust via C++
description: "Get current permissions of PDF-document."
type: docs
url: /rust-cpp/security/get_permissions/
---

_Get current permissions of PDF-document._

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
    // Open a password-protected PDF-document
    let pdf = Document::open_with_password("sample_with_permissions.pdf", "ownerpass")?;

    // Get current permissions of PDF-document
    let permissions: Permissions = pdf.get_permissions()?;

    // Print permissions
    println!("Permissions: {}", permissions);

    Ok(())
}

```