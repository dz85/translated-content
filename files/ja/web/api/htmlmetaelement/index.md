---
title: HTMLMetaElement
slug: Web/API/HTMLMetaElement
page-type: web-api-interface
tags:
  - API
  - HTML DOM
  - インターフェイス
  - リファレンス
browser-compat: api.HTMLMetaElement
translation_of: Web/API/HTMLMetaElement
---
{{ APIRef("HTML DOM") }}

**`HTMLMetaElement`** インターフェイスは、文書に関する説明的なメタデータが入ります。 {{domxref("HTMLElement")}} インターフェイスから、すべてのプロパティとメソッドを継承しています。

{{InheritanceDiagram}}

## プロパティ

_親である {{domxref("HTMLElement")}} からプロパティを継承しています。_

| 名前                                  | 型                             | 説明                                                                            |
| ------------------------------------- | -------------------------------- | -------------------------------------------------------------------------------------- |
| `content`                             | 文字列 | メタデータプロパティの値を取得または設定します。                                          |
| `httpEquiv`                           | 文字列 | 文書に定義する HTTP レスポンスヘッダーの名前を取得または設定します。             |
| `name`                                | 文字列 | 文書に定義するメタデータプロパティの名前を取得または設定します。                |
| `scheme` {{deprecated_inline}} | 文字列 | メタデータプロパティの値を解釈するために使用されるスキームの名前を取得または設定します。 |

## メソッド

_固有のメソッドはありません。親である {{domxref("HTMLElement")}} からメソッドを継承しています。_

## 仕様書

{{Specifications}}

## ブラウザーの互換性

{{Compat}}

## 関連情報

- このインターフェイスを実装している HTML 要素: {{HTMLElement("meta")}}
