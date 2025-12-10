---
title: "decrypt"
second_title: Aspose.PDF for Rust via C++
description: "Decrypt PDF-document."
type: docs
url: /rust-cpp/security/decrypt/
---

_Decrypt PDF-document._

```rust
pub fn decrypt(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a password-protected PDF-document
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Decrypt PDF-document
    pdf.decrypt()?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_decrypt.pdf")?;

    Ok(())
}

```