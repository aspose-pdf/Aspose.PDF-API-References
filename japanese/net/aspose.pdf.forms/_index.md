---
title: Aspose.Pdf.Forms
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms 名前空間には、フォーム（標準、静的、動的）およびテキストボックス、リストボックス、ラジオボタンなどのさまざまなタイプのフィールドを説明するクラスがあります。
type: docs
weight: 110
url: /ja/net/aspose.pdf.forms/
---
**Aspose.Pdf.Forms** 名前空間には、フォーム（標準、静的、動的）およびテキストボックス、リストボックス、ラジオボタンなどのさまざまなタイプのフィールドを説明するクラスがあります。

## クラス

| クラス | 説明 |
| --- | --- |
| [BarcodeField](./barcodefield/) | バーコードフィールドを表すクラス。 |
| [ButtonField](./buttonfield/) | プッシュボタンフィールドを表すクラス。 |
| [CheckboxField](./checkboxfield/) | チェックボックスフィールドを表すクラス。 |
| [ChoiceField](./choicefield/) | 選択フィールドの基底クラスを表します。 |
| [ComboBoxField](./comboboxfield/) | フォームのコンボボックスフィールドを表すクラス。 |
| [DateField](./datefield/) | カレンダー表示のある日付フィールド。 |
| [DocMDPSignature](./docmdpsignature/) | ドキュメントMDP（変更検出および防止）署名タイプのクラスを表します。 |
| [ExternalSignature](./externalsignature/) | X509Certificate2を使用して、切り離されたPKCS#7署名を作成します。USBスマートカードやエクスポート可能な秘密鍵を持たないトークンをサポートしています。 |
| [Field](./field/) | アクロフォームフィールドの基底クラス。 |
| [FileSelectBoxField](./fileselectboxfield/) | ファイル選択ボックス要素のフィールド。 |
| [Form](./form/) | フォームオブジェクトを表すクラス。 |
| [IconFit](./iconfit/) | ウィジェット注釈のアイコンがその注釈の矩形内でどのように表示されるかを説明します。 |
| [ListBoxField](./listboxfield/) | ListBoxフィールドを表すクラス。 |
| [NumberField](./numberfield/) | 指定された有効文字を持つテキストフィールド。 |
| [Option](./option/) | 選択フィールドのオプションを表すクラス。 |
| [OptionCollection](./optioncollection/) | 選択フィールドのオプションのコレクションを表すクラス。 |
| [PasswordBoxField](./passwordboxfield/) | パスワードを入力するためのテキストフィールドを説明するクラス。 |
| [PKCS1](./pkcs1/) | PKCS#1標準に関する署名オブジェクトを表します。RSA暗号化アルゴリズムとSHA-1ダイジェストメソッドが署名に使用されます。 |
| [PKCS7](./pkcs7/) | インターネットRFC 2315のPKCS#7仕様に準拠したPKCS#7オブジェクトを表します。ドキュメントのバイト範囲の`SHA1ダイジェスト`がPKCS#7 SignedDataフィールドにカプセル化されています。 |
| [PKCS7Detached](./pkcs7detached/) | インターネットRFC 2315のPKCS#7仕様に準拠したPKCS#7オブジェクトを表します。ドキュメントのバイト範囲に対する元の署名メッセージダイジェストが通常のPKCS#7 SignedDataフィールドとして組み込まれています。PKCS#7 SignedDataフィールドにはデータはカプセル化されません。 |
| [RadioButtonField](./radiobuttonfield/) | ラジオボタンフィールドを表すクラス。 |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | RadioButtonフィールドのアイテムを表すクラス。 |
| [RichTextBoxField](./richtextboxfield/) | リッチテキストエディタコンポーネントを説明するクラス。 |
| [Signature](./signature/) | PDFドキュメント内の署名オブジェクトを表す抽象クラス。署名は署名オブジェクトの値を持つフィールドであり、最後のものはドキュメントの有効性を検証するために使用されるデータを含みます。 |
| [SignatureCustomAppearance](./signaturecustomappearance/) | 署名のカスタム外観オブジェクトを表す抽象クラス。 |
| [SignatureField](./signaturefield/) | 署名フォームフィールドを表します。 |
| [SignHash](./signhash/) | ドキュメントハッシュをカスタム署名するためのデリゲート。 |
| [TextBoxField](./textboxfield/) | テキストボックスフィールドを表すクラス。 |
| [XFA](./xfa/) | XMLフォームをXMLフォームアーキテクチャ（XFA）に関して表します。 |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [BoxStyle](./boxstyle/) | チェックボックスでチェックを描画するためのスタイルを表します。 |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | このドキュメントに付与されたアクセス許可。 有効な値は次のとおりです：1 - ドキュメントに対する変更は許可されていません。ドキュメントへの変更は署名を無効にします。2 - 許可される変更はフォームの記入、ページテンプレートのインスタンス化、および署名です。他の変更は署名を無効にします。3 - 許可される変更は2と同じで、注釈の作成、削除、および変更も含まれます。他の変更は署名を無効にします。 |
| [FormType](./formtype/) | アクロフォームの可能なタイプの列挙型。 |
| [IconCaptionPosition](./iconcaptionposition/) | アイコンの位置を説明します。 |
| [ScalingMode](./scalingmode/) | 使用されるスケーリングのタイプ。 |
| [ScalingReason](./scalingreason/) | アイコンが注釈の矩形内でスケーリングされる状況。 |
| [SubjectNameElements](./subjectnameelements/) | 署名の主題文字列内の要素を説明する列挙型。 |
| [Symbology](./symbology/) | （バーコード）シンボロジーは、特定のタイプのバーコードの技術的詳細を定義します：バーの幅、文字セット、エンコーディング方法、チェックサム仕様など。 |