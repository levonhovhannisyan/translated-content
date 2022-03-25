---
title: ':-moz-locale-dir(rtl)'
slug: 'Web/CSS/:-moz-locale-dir(rtl)'
tags:
  - CSS
  - Mozilla 拡張
  - Right-to-left
  - リファレンス
  - ローカライズ
  - 右書き
  - 標準外
  - 疑似クラス
translation_of: 'Web/CSS/:-moz-locale-dir(rtl)'
---
<div>{{CSSRef}}{{Non-standard_header}}{{gecko_minversion_header("1.9.2")}}</div>

[CSS](/ja/docs/Web/CSS) の <strong>`:-moz-locale-dir(ltr)`</strong> [疑似クラス](/ja/docs/Web/CSS/pseudo-classes)は [Mozilla 拡張](/ja/docs/Web/CSS/Mozilla_Extensions)であり、ユーザーインターフェイスが右から左へ向けて表示される要素に一致します。これは設定の `intl.uidirection.<em>locale</em>` (`<em>locale</em>` は現在のロケール) が "rtl" に設定されていることで特定されます。

<div class="note">
<strong>メモ:</strong> 擬似クラスは、主に拡張機能及びテーマをユーザーのロケールに基づいて適合させるために使用されます。 (これは、ウィンドウとウィンドウ、またタブとタブの間でも変えることができます。) また、拡張機能がユーザーの既定のロケールに対応しなくても動作させることができるため、ロケールの仕様を気にしなくても、左から右方向、右から左方向の両方のレイアウトに対応できます。
</div>

<div class="warning">
このセレクターは HTML では正しく機能しません。ユーザーインターフェイスのロケールが右方向か左方向かに関わらず、常に一致しません。
</div>

<h2 id="Example" name="Example">例</h2>

<h3 id="HTML">HTML</h3>

<pre class="brush: html">&lt;p&gt;If you're using a right-to-left interface, this should be red.&lt;/p&gt;
</pre>

<h3 id="CSS">CSS</h3>

<pre class="brush: css">p:-moz-locale-dir(ltr) {
  color: red;
}</pre>

<h3 id="Result" name="Result">結果</h3>

{{EmbedLiveSample("Example")}}

<h2 id="See also" name="See also">関連情報</h2>

<ul>
 <li>{{cssxref(":dir",":dir(…)")}}</li>
 <li>{{cssxref(":-moz-locale-dir(ltr)")}}</li>
 <li>[テーマが RTL のロケールで動作するようことを確認する](/ja/docs/Making_Sure_Your_Theme_Works_with_RTL_Locales)</li>
</ul>