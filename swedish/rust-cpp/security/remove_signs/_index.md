---
title: "remove_signs"
second_title: "Aspose.PDF för Rust via C++"
description: "Ta bort signaturer från PDF-dokument."
type: docs
url: /sv/rust-cpp/security/remove_signs/
---

_Ta bort signaturer från PDF-dokumentet._

```rust
pub fn remove_signs(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the resulting PDF-document without signatures


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med namnet "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Ta bort signaturer från PDF-dokumentet
    pdf.remove_signs("sample_remove_signs.pdf")?;

    Ok(())
}

```