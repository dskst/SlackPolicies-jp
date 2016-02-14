# Security Practices

We take the security of your data very seriously at Slack.  
Slackはお客様のデータセキュリティに対して真剣に取り組んでいます。

As transparency is one of the principles on which our company is built, we aim to be as clear and open as we can about the way we handle security.  
透明性は当社が構築されている原則の1つなので、セキュリティの扱いに関することができる限り明確かつオープンであることを目指しています。

## Confidentiality - 機密性

We place strict controls over our employees’ access to the data you and your users make available via the Slack services, as more specifically defined in your agreement with Slack covering the use of the Slack services ("Customer Data"), and are committed to ensuring that Customer Data is not seen by anyone who should not have access to it.  
Slackでやり取りしたデータについてSlack社員のアクセス権限を厳密に管理しています。具体的にはSlackの契約書で定義されており、権限を持たない何者もアクセスができないことを約束します。

The operation of the Slack services requires that some employees have access to the systems which store and process Customer Data.   
Slackの運用では、一部の従業員が顧客データシステムへのアクセス権を持っている必要があります。

For example, in order to diagnose a problem you are having with the Slack services, we may need to access your Customer Data.  
たとえば、あなたがSlackで抱えている問題を解決するために、我々はあなたのデータにアクセスする必要があるかもしれません。

These employees are prohibited from using these permissions to view Customer Data unless it is necessary to do so.
これらの従業員は、そうする必要がある場合を除いて、権限を使用して顧客データを表示することは禁止されています。

We have technical controls and audit policies in place to ensure that any access to Customer Data is logged.  
我々は、顧客データへのアクセスを確実に記録するために、技術的コントロールと監査ポリシーを持っています。

All of our employees and contract personnel are bound to our policies regarding Customer Data and we treat these issues as matters of the highest importance within our company.  
すべての従業員と契約担当者が、顧客データに関する方針義務に従うことは、私たちの会社の最高重要事項として認識しています。

## Personnel Practices - 人事慣習

Slack conducts background checks on all employees before employment, and employees receive security training during onboarding as well as on an ongoing basis.  
Slackは雇用前に従業員の信用調査を行い、研修期間だけではなく継続的にセキュリティトレーニングを受けます。

All employees are required to read and sign our comprehensive information security policy covering the security, availability, and confidentiality of the Slack services.  
すべての従業員は、Slackのセキュリティ、可用性、および機密性に関する情報セキュリティポリシーを読んで署名する必要があります。

## Compliance - コンプライアンス

The following security-related audits and certifications are applicable to the Slack services:  
次のセキュリティ関連の監査および認定資格はSlackに適用されます。

* ***Service Organization Control (SOC) Reports:*** Slack has undergone a SOC 2 audit, and a copy of Slack’s most recent report is available upon request from your Account Manager.  
***SOCレポート:*** Slackは、SOC2監査を受けており、最新のレポートはアカウントマネージャーからの要求に応じて入手可能です。
* ***PCI:*** Slack is not currently a PCI-certified Service Provider. We are a PCI Level 4 Merchant and have completed the Payment Card Industry Data Security Standard’s SAQ-A, allowing us to use a third party to process your credit card information securely.  
***PCI:*** Slackは現在、PCI認定サービスプロバイダではありません。私たちはPCIレベル4加盟店であり、PCIデータセキュリティスタンダード SAQ-Aを取得し、より安全にクレジットカード情報を処理するために第三者機関を使用しています。

The environment that hosts the Slack services maintains multiple certifications for its data centers, including ISO 27001 compliance, PCI Certification, and SOC reports.  
Slackのホスティング環境は、データセンターのための資格、ISO27001準拠、PCI認定を維持しているとSOCによってレポートされています。

For more information about their certification and compliance, please visit the AWS Security website and the AWS Compliance website.  
認定および準拠の詳細については、AWSセキュリティWebサイトおよびAWSコンプライアンスのウェブサイトをご覧ください。

## Security Features for Team Members & Administrators - チームメンバー＆管理者のためのセキュリティ機能

In addition to the work we do at the infrastructure level, we provide team administrators of paid versions of the Slack services with additional tools to enable their own users to protect their Customer Data.  
顧客データを保護するため、Slackの有料版と追加ツールをチーム管理者に提供することにより、インフラストラクチャ・レベルに加えて独自ユーザーを有効にすることができます。

### Access Logging - アクセスログ

Detailed access logs are available both to users and administrators of paid teams.  
詳細なアクセスログは、有料チームのユーザーと管理者の両方が利用できます。

We log every time an account signs in, noting the type of device used and the IP address of the connection.  
サインインするたびに、使用しているデバイスの種類や接続IPアドレスをロギングします。

Team administrators and owners of paid teams can review consolidated access logs for their whole team.   
有料チームの管理者とのオーナーは、統合アクセスログを確認することができます。

We also make it easy for administrators to remotely terminate all connections and sign out all devices authenticated to the Slack services at any time, on-demand.  
また、管理者がリモートからすべての接続を終了、すべてのデバイスをサインアウトさせることが、オンデマン
ドで簡単に行うことができます。

### Team-Wide Two-Factor Authentication - チーム全体の二段階認証

Team administrators can require all users to set up two-factor authentication on their accounts. Instructions for doing this are available on our support center.  
チーム管理者は、アカウントセットアップの2段階認証を必須にすることができます。実施するための手順については、弊社サポートセンターで入手できます。

### Single Sign On - シングルサインオン

Administrators of paid teams can integrate their Slack services instance with a variety of single-sign-on providers.
有料チームの管理者は、様々なシングル・サインオンプロバイダのサービスをSlackに統合することができます。

Teams on the ‘Standard’ plan can enable Google Apps for Domains as their authentication provider, and teams on the ‘Plus’ plan can enable SAML SSO with providers such as OneLogin, Okta, and Ping Identity.  
スタンダードプランはGoogle Appsを認証プロバイダとして利用することができ、プラスプランは SAML SSO として OneLogin, Okta, そして Ping Identity を使用することができます。

### Data Retention - データ保持

Owners of paid Slack teams can configure custom message retention policies on a team-wide and per-channel basis.  
有料チームオーナーは、チーム全体およびチャネルごとにカスタムメッセージ保持ポリシーを設定することができます。

Setting a custom duration for retention means that messages or files older than the duration you set will be deleted on a nightly basis.  
データ保持時間をカスタム設定すると、あなたが設定した時間よりも古いメッセージまたはファイルは毎晩削除されます。

### Deletion of Customer Data - 顧客データの削除

Slack provides the option for team owners to delete Customer Data at any time during a subscription term.  
チームのオーナーは、サブスクリプション期間中のいつでも顧客データを削除することができます。

Within 24 hours of team owner initiated deletion, Slack hard deletes all information from currently-running production systems (excluding team and channel names, and search terms embedded in URLs in web server access logs).  
チームのオーナーが削除を開始すると24時間以内に、現在実行中の本番システムからすべての情報が物理削除されます（チームとチャンネル名、Webサーバアクセスログ内のURLに埋め込まれた検索ワードを除く）。

### Return of Customer Data - 顧客データの帰属

The Slack services include the following export capabilities:  
Slackは、次のエクスポート機能が含まれます。

* ***Standard Exports:*** During a subscription term administrators of any Slack services plan can export Customer Data from team channels, but not from direct messages or private channels.  
