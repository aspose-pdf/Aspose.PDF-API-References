---
title: "cifra"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Cifra il PDF-document."
type: docs
url: /it/rust-cpp/security/encrypt/
---

_Cifra PDF-document._

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
    // Crea un nuovo PDF-document
    let pdf = Document::new()?;

    // Cifra PDF-document
    pdf.encrypt(
        "userpass",  // User password
        "ownerpass", // Owner password
        Permissions::PRINT_DOCUMENT | Permissions::MODIFY_CONTENT | Permissions::FILL_FORM, // Permissions bitmask
        CryptoAlgorithm::AESx128, // Encryption algorithm
        true,                     // Use PDF 2.0 encryption
    )?;

    // Salva il PDF-document cifrato
    pdf.save_as("sample_with_password.pdf")?;

    Ok(())
}

```