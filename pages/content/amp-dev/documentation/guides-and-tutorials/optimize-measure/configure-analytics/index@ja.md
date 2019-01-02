---
$title: アナリティクスを設定する
---

## 開始前に決めておくこと

アナリティクス ソリューションを設定するためには、その種類を問わず、必要なデータと
その分析方法をあらかじめ把握しておく必要があります。設定前に次のことを決めておいてください。

* ユーザー エンゲージメント分析にサードパーティのアナリティクス ツールを使用するか、
社内のソリューションを使用するか。
* ユーザー エンゲージメントを把握するために、ユーザーのどのような行動を測定するか。

### ベンダーと社内、どちらにデータを送信するか

ユーザー エンゲージメントの測定に社内のソリューションを使用する場合は、
URL さえあれば、AMP アナリティクスをそのソリューションと統合できます。
この URL がデータの送信先となります。
データは複数の URL に送信できるため、
たとえばページビュー データと
ソーシャル エンゲージメント データをそれぞれ別の URL に送信できます。

AMP アナリティクスでは、1 回の測定で得たデータを複数の URL に送信できます。
すでに 1 社以上のアナリティクス ベンダーを利用している場合は、
[アナリティクス ベンダー]({{g.doc('/content/amp-dev/documentation/guides-and-tutorials/optimize-measure/configure-analytics/analytics-vendors.md', locale=doc.locale).url.path}})の一覧で、該当のソリューションが AMP と統合されているかどうかをご確認ください。
統合済みの場合は、設定の詳細情報を確認し、その手順に沿って対応してください。

アナリティクス ベンダーが AMP を統合していない場合は、
ベンダーに問い合わせてサポートを依頼してください。
あわせて、[AMP プロジェクトに問題を報告](https://github.com/ampproject/amphtml/issues/new)し、
ベンダーを追加するようリクエストすることをおすすめします。
また、
[AMP HTML にアナリティクス ツールを統合する](https://github.com/ampproject/amphtml/blob/master/extensions/amp-analytics/integrating-analytics.md)方法もご確認ください。

### どのようなデータが必要か

エンゲージメントを測定するためには、どのようなユーザーデータを収集する必要があるでしょうか。
設定の前に、必要なデータを判断しておく必要があります。

その際には、次の点を考慮してください。

* ページビューのみをトラッキングするか、その他のユーザー エンゲージメント パターンもトラッキングするか
（[amp-pixel と amp-analytics](/ja/docs/analytics/analytics_basics.html#amp-pixel-または-amp-analytics-を使う) についての説明もご確認ください）。
* ユーザー、コンテンツ、端末、ブラウザについて、
どのようなデータを収集するか（[変数置換](/ja/docs/analytics/analytics_basics.html#置換変数)についての説明もご確認ください）。
* ユーザーをどのように識別するか（[ユーザーの識別](/ja/docs/analytics/analytics_basics.html#ユーザー認証)についての説明もご確認ください）。


[tip type="read-on"]

アナリティクスのさらに詳しい内容については、[アナリティクス: 基本]({{g.doc('/content/amp-dev/documentation/guides-and-tutorials/optimize-measure/configure-analytics/analytics_basics.md', locale=doc.locale).url.path}})をご覧ください。

[/tip]
