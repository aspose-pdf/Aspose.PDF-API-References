---
title: "PdfFileSecurity"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa a criptografia ou descriptografia de um arquivo Pdf com senha de proprietário ou de usuário, alterando a configuração de segurança e a senha."
type: docs
weight: 300
url: /pt/python-net/aspose.pdf.facades/pdffilesecurity/
---

## PdfFileSecurity class

Representa a criptografia ou descriptografia de um arquivo Pdf com senha de proprietário ou de usuário, alterando a configuração de segurança e a senha.

O tipo PdfFileSecurity expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| PdfFileSecurity(input_stream, output_stream) | Inicializa uma nova instância da classe PdfFileSecurity |
| PdfFileSecurity(input_file, output_file) | Inicializa uma nova instância da classe PdfFileSecurity |
| PdfFileSecurity() | Inicializa o objeto PdfFileSecurity. |
| PdfFileSecurity(document) | Inicializa uma nova instância da classe PdfFileSecurity |
| PdfFileSecurity(document, output_file) | Inicializa uma nova instância da classe PdfFileSecurity |
| PdfFileSecurity(document, output_stream) | Inicializa uma nova instância da classe PdfFileSecurity |
## Propriedades
| Nome | Descrição |
| :- | :- |
| document | Obtém a fachada do documento em que está trabalhando. |
| allow_exceptions | Se este valor for definido como true, uma exceção será lançada em caso de falha na operação. Caso contrário, o método retorna false na falha e a última exceção pode ser verificada com a propriedade LastException. |
## Métodos
| Nome | Descrição |
| :- | :- |
| bind_pdf(src_file) | Inicializa a fachada. |
| bind_pdf(src_stream) | Inicializa a fachada. |
| bind_pdf(src_doc) | Vincula o documento PDF para edição. |
| save(dest_file) | Salva o documento PDF no arquivo especificado. |
| save(dest_stream) | Salva o documento PDF no fluxo especificado. |
| encrypt_file(user_password, owner_password, privilege, key_size) | Criptografa o arquivo Pdf com a senha do usuário e a senha do proprietário e define os privilégios de acesso do documento.<br/>            A senha do usuário e a senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída <br/>            por uma string aleatória se a senha do proprietário de entrada for nula ou vazia.<br/>            Lança exceção se o processo falhar. |
| encrypt_file(user_password, owner_password, privilege, key_size, cipher) | Criptografa o arquivo Pdf com a senha do usuário e a senha do proprietário e define os privilégios de acesso do documento.<br/>            A senha do usuário e a senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída <br/>            por uma string aleatória se a senha do proprietário de entrada for nula ou vazia.<br/>            Existem 6 combinações possíveis de valores de KeySize e Algorithm. <br/>            No entanto, (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) são inválidos e a <br/>            exceção correspondente será levantada se o kit encontrar essa combinação.<br/>            Lança uma exceção se o processo falhar. |
| set_privilege(privilege) | Define a segurança do arquivo Pdf com senhas de usuário/proprietário vazias.<br/>            A senha do proprietário será adicionada por uma string aleatória.<br/>            Lança uma exceção se o processo falhar. |
| set_privilege(user_password, owner_password, privilege) | Define a segurança do arquivo Pdf com a senha original.<br/>            Lança uma exceção se o processo falhar. |
| change_password(owner_password, new_user_password, new_owner_password) | Altera a senha do usuário e a senha do proprietário usando a senha do proprietário, mantendo as configurações de segurança originais.<br/>             A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída <br/>             por uma string aleatória se a nova senha do proprietário for nula ou vazia.<br/>             Lança uma exceção se o processo falhar. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | Altera a senha do usuário e a senha usando a senha do proprietário, permitindo redefinir a segurança do documento Pdf.<br/>            A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída <br/>            por uma string aleatória se a nova senha do proprietário for nula ou vazia.<br/>            Lança uma exceção se o processo falhar. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | Altera a senha do usuário e a senha pelo senha do proprietário, permitindo redefinir a segurança do documento Pdf.<br/>            A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída <br/>            por uma string aleatória se a nova senha do proprietário for nula ou vazia.<br/>            Existem 6 combinações possíveis de valores de KeySize e Algorithm. <br/>            No entanto, (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) são inválidos e a <br/>            exceção correspondente será lançada se o kit encontrar essa combinação.<br/>            Lança uma exceção se o processo falhar. |
| try_change_password(owner_password, new_user_password, new_owner_password) | Altera a senha do usuário e a senha do proprietário usando a senha do proprietário, mantendo as configurações de segurança originais.<br/>             A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída <br/>             Não lança uma exceção se o processo falhar.<br/>             por uma string aleatória se a nova senha do proprietário for nula ou vazia. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | Altera a senha do usuário e a senha pelo senha do proprietário, permitindo redefinir a segurança do documento Pdf.<br/>            A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída <br/>            por uma string aleatória se a nova senha do proprietário for nula ou vazia.<br/>            Não lança uma exceção se o processo falhar. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | Altera a senha do usuário e a senha pelo senha do proprietário, permitindo redefinir a segurança do documento Pdf.<br/>            A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída <br/>            por uma string aleatória se a nova senha do proprietário for nula ou vazia.<br/>            Existem 6 combinações possíveis de valores de KeySize e Algorithm. <br/>            No entanto, (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) são inválidos e a <br/>            exceção correspondente será lançada se o kit encontrar essa combinação.<br/>            Não lança uma exceção se o processo falhar. |
| close() | Fecha a fachada. |
| try_encrypt_file(user_password, owner_password, privilege, key_size) | Criptografa o arquivo Pdf com a senha do usuário e a senha do proprietário e define as permissões do documento para acesso.<br/>            A senha do usuário e a senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída <br/>            por uma string aleatória se a senha do proprietário de entrada for nula ou vazia.<br/>            Não lança uma exceção se o processo falhar. |
| decrypt_file(owner_password) | Descriptografa um documento Pdf criptografado usando a senha do proprietário. <br/>            Se o documento não possuir senha do proprietário, é permitido usar a senha do usuário.<br/>            Lança uma exceção se o processo falhar. |
| try_decrypt_file(owner_password) | Descriptografa um documento Pdf criptografado usando a senha do proprietário. <br/>            Se o documento não possuir senha do proprietário, é permitido usar a senha do usuário.<br/>            Não lança uma exceção se o processo falhar. |
| try_set_privilege(user_password, owner_password, privilege) | Define a segurança do arquivo Pdf com a senha original.<br/>            Não lança uma exceção se o processo falhar. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

