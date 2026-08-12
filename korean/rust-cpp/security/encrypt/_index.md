---
title: "암호화"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF-document를 암호화합니다."
type: docs
url: /ko/rust-cpp/security/encrypt/
---

_PDF-document을 암호화합니다._

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
    // 새 PDF 문서를 생성합니다
    let pdf = Document::new()?;

    // PDF-document을 암호화합니다
    pdf.encrypt(
        "userpass",  // User password
        "ownerpass", // Owner password
        Permissions::PRINT_DOCUMENT | Permissions::MODIFY_CONTENT | Permissions::FILL_FORM, // Permissions bitmask
        CryptoAlgorithm::AESx128, // Encryption algorithm
        true,                     // Use PDF 2.0 encryption
    )?;

    // 암호화된 PDF-document을 저장합니다
    pdf.save_as("sample_with_password.pdf")?;

    Ok(())
}

```