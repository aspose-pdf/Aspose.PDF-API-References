---
title: "decrypt"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Dekripsi dokumen PDF."
type: docs
url: /id/rust-cpp/security/decrypt/
---

_Dekripsi PDF-document._

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
    // Buka PDF-document yang dilindungi kata sandi
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Dekripsi PDF-document
    pdf.decrypt()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_decrypt.pdf")?;

    Ok(())
}

```