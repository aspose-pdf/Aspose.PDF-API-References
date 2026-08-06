---
title: "verschlüsseln"
second_title: "Aspose.PDF für Rust über C++"
description: "Verschlüssele das PDF-Dokument."
type: docs
url: /de/rust-cpp/security/encrypt/
---

_Verschlüsseln PDF-Dokument._

```rust
pub fn encrypt(
    &self,
    user_password: &str,
    owner_password: &str,
    permissions: Permissions,
    crypto_algorithm: CryptoAlgorithm,
    use_pdf_20: bool,
) -> Result<(), PdfError>
```

**Arguments**
  * **user_password** - the user password
  * **owner_password** - the owner password
  * **permissions** - the allowed permissions (bitflags `Permissions`)
  * **crypto_algorithm** - the encryption algorithm (`CryptoAlgorithm` enum)
  * **use_pdf_20** - whether to use PDF 2.0 encryption

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{CryptoAlgorithm, Document, Permissions};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Erstelle ein neues PDF-Dokument
    let pdf = Document::new()?;

    // Verschlüsseln PDF-Dokument
    pdf.encrypt(
        "userpass",  // User password
        "ownerpass", // Owner password
        Permissions::PRINT_DOCUMENT | Permissions::MODIFY_CONTENT | Permissions::FILL_FORM, // Permissions bitmask
        CryptoAlgorithm::AESx128, // Encryption algorithm
        true,                     // Use PDF 2.0 encryption
    )?;

    // Speichern Sie das verschlüsselte PDF-Dokument
    pdf.save_as("sample_with_password.pdf")?;

    Ok(())
}

```