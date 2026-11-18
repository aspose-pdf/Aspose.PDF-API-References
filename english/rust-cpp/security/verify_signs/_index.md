---
title: "verify_signs"
second_title: Aspose.PDF for Rust via C++
description: "Verify signs from PDF-document."
type: docs
url: /rust-cpp/security/verify_signs/
---

_Verify signs from PDF-document._

```rust
pub fn verify_signs(&self) -> Result<Vec<PdfSignStatus>, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Vec\<PdfSignStatus\>)** - the `Vec` of `PdfSignStatus` structs, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document named "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Verify signs from PDF-document
    let signs = pdf.verify_signs()?;

    // Print their status
    for sign in signs {
        println!("Signature: {}, Status: {}", sign.name, sign.status);
    }

    Ok(())
}
```