---
title: "kryptera"
second_title: "Aspose.PDF för Rust via C++"
description: "Kryptera PDF-dokument."
type: docs
url: /sv/rust-cpp/security/encrypt/
---

_Kryptera PDF-dokument._

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
    // Skapa ett nytt PDF-dokument
    let pdf = Document::new()?;

    // Kryptera PDF-dokument
    pdf.encrypt(
        "userpass",  // User password
        "ownerpass", // Owner password
        Permissions::PRINT_DOCUMENT | Permissions::MODIFY_CONTENT | Permissions::FILL_FORM, // Permissions bitmask
        CryptoAlgorithm::AESx128, // Encryption algorithm
        true,                     // Use PDF 2.0 encryption
    )?;

    // Spara det krypterade PDF-dokumentet
    pdf.save_as("sample_with_password.pdf")?;

    Ok(())
}

```