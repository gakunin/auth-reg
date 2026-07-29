---
hide:
  - navigation
---



# Update(最終更新日 2026/07/29)
- 2026/07/29 登録済み認証器に以下を追加
    - Appleパスワードマネージャ
    - Googleパスワードマネージャ
    - OTPManager
- 2026/07/29 認証器運用時のリスク評価シートを第3版に更新（パスワードマネージャを評価対象に追加）
- 2025/06/16 登録済み認証器に以下を追加
    - Authenticator(Authenticator.cc)
    - WinAuth
    - tiqr
- 2025/06/16 認証器運用時のリスク評価シートをアップデート
- 2024/08/26 関連情報の資料に以下を追加
    - 資料
        - NIST SP 800-63Bsup1 和訳


# 登録済み認証器

## 登録済み認証器一覧

| 認証器名または準拠標準 | 認証器バージョン | 提供会社 | 認証器種類 | 認証器カテゴリ | 要素 |  |  | 承認日 | 審査学認基準 | 記載情報更新日 |
| - | - | - | - | - | - | - | - | - | - | - |
| | | | | | 所持 | 生体 | 知識 | | | |
| [Google Authenticator](authenticator/g_authenticator.md) | 6.0 | Google | Single-Factor OTP Device（単要素OTPデバイス） | 単要素 | 〇 | | | 2024/2/29 | Ver.1.0 | 2024/4/1 |
| [Microsoft Authenticator](authenticator/ms_authenticator.md) | 6.2312.8150 | Microsoft | Single-Factor OTP Device（単要素OTPデバイス） | 単要素 | 〇 | | | 2024/2/29 | Ver.1.0 | 2024/4/1 |
| [FIDO(FIDO2)](authenticator/fido.md) | 1.2 Proposed Standard | FIDO Allianceの仕様に基づき設計や製造を行う認証器メーカ | Multi-Factor Cryptographic Device（多要素暗号デバイス） | 多要素 | 〇 | □ | □ | 2024/2/29 | Ver.1.0 | 2024/4/1 |
| [FIDO(CTAP1(U2F))](authenticator/fido.md) | 1.2 Proposed Standard | FIDO Allianceの仕様に基づき設計や製造を行う認証器メーカ | Single-Factor Cryptographic Device（単要素暗号デバイス） | 単要素 | 〇 | | | 2024/2/29 | Ver.1.0 | 2024/4/1 |
| [FIDO(UAF)](authenticator/fido.md) | 1.2 Proposed Standard | FIDO Allianceの仕様に基づき設計や製造を行う認証器メーカ | Multi-Factor Cryptographic Device（多要素暗号デバイス） | 多要素 | 〇 | □ | □ | 2024/2/29 | Ver.1.0 | 2024/4/1 |
| [UPKI電子証明書発行サービス・クライアント証明書](authenticator/upki_clientcert.md) | 2023年12月14日の仕様変更準拠 | SECOM Trust Systems Co., Ltd. | Single-Factor Cryptographic Software（単要素暗号ソフトウェア） | 単要素 | 〇 | | | 2024/3/29 | Ver.1.0 | 2024/4/1 |
| [tiqr](authenticator/tiqr.md)          | iOS(3.3.2), Android(4.1.1) | SURF B.V.            | Out-of-Band Device（経路外デバイス）         | 単要素 | 〇 |   |   | 2025/3/31 | Ver.1.0 | 2025/3/31 |
| [Authenticator](authenticator/authenticator_cc.md) | 8.0.1                      | mymindstorm, Sneezry | Single-Factor OTP Device（単要素OTPデバイス） | 単要素 | 〇 |   |   | 2025/3/31 | Ver.1.0 | 2025/3/31 |
| [WinAuth](authenticator/winauth.md)       | 3.5.1                      | Colin Mackie.        | Single-Factor OTP Device（単要素OTPデバイス） | 単要素 | 〇 |   |   | 2025/3/31 | Ver.1.0 | 2025/3/31 |
| [Appleパスワードマネージャ](authenticator/apple_password_manager.md) | 2026/3/5時点の状況 | Apple Inc. | Memorized Secret（記憶シークレット）／Multi-Factor Cryptographic Software（多要素暗号ソフトウェア）／Single-Factor OTP Device（単要素OTPデバイス） | パスワードマネージャ | 〇 | 〇 | 〇 | 2026/3/31 | Ver.1.0 | 2026/3/31 |
| [Googleパスワードマネージャ](authenticator/google_password_manager.md) | 2026/3/5時点の状況 | Google LLC | Memorized Secret（記憶シークレット）／Multi-Factor Cryptographic Software（多要素暗号ソフトウェア） | パスワードマネージャ | 〇 | 〇 | 〇 | 2026/3/31 | Ver.1.0 | 2026/3/31 |
| [OTPManager](authenticator/stickybit_otp_manager.md) | 1.0.7(iOS), 2.1.9(macOS) | Sticky Bit（Carlos de Boer Ver Voorn） | Single-Factor OTP Device（単要素OTPデバイス） | 単要素 | 〇 |   |   | 2026/6/1 | Ver.1.0 | 2026/6/1 |


”□"はいずれかを選択する。
