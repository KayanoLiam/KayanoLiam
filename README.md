# こんにちは、KayanoLiam です 👋

**chenchen** / 茅野遥華  
日本にいる学部生。バグを直したり、ドキュメントの誤字を直して「コントリビューター」を名乗ったりしています。

> 「コードを書くより、先に README を書くタイプです。」  
> — たぶん私

---

## いま作っているもの

### [ContextX](https://github.com/KayanoLiam/ContextX) ✨
**無料のリモート MCP サーバー** — Grok で「普通に調べる」と「本気で調べる」の二段構え。

| モード | 中身 | 気分 |
|--------|------|------|
| 通常検索 | Grok 4.3 | コンビニのコーヒー |
| 深度検索 | Grok 4.20 Multi-Agent | 深夜のスペシャルティ |

- API キー不要。バイナリも不要。URL を足すだけ
- ストリーミングなので、ゲートウェイに「待たせすぎ」と怒られにくい
- 公開エンドポイント: `https://mcp.twitter.monster/mcp`
- 言語: Rust（速いふりができる）
- Stars: がんばって増やしています ⭐

Cursor / Claude Code / Pi などに足せます。詳しくは [README](https://github.com/KayanoLiam/ContextX) をどうぞ（日本語・中文・English あります）。

---

## マージしてもらった PR（自慢コーナー）

大きなプロジェクトに少しだけ手を入れた記録です。偉そうに見せますが、中身は地味です。

### 😅 [tokio-rs/axum#3890](https://github.com/tokio-rs/axum/pull/3890)
**docs: fix route_service example for Body API**

はい、**ドキュメントだけ**です。  
実行時の挙動は1ミリも変わっていません。でも「axum にマージされた」と言うと、だいたいみんな「おお…」となります。  
（ドキュメントも大事だよ？　例が古いと、みんなが同じ沼に落ちるから。）

### ✅ [sveltejs/kit#17106](https://github.com/sveltejs/kit/pull/17106)
**fix: follow HTTP redirects after enhanced form submissions**

フォーム送信のあとにリダイレクトをちゃんと追う修正。  
「送信したのに画面が微妙に変」系のやつです。

### ✅ [sveltejs/kit#17107](https://github.com/sveltejs/kit/pull/17107)
**fix: preserve the document path in hash-router resolve**

ハッシュルーターでパスが消えないようにした修正。  
URL の `#` のあとを大事に扱うタイプの話です。

### ✅ [QwikDev/qwik#9010](https://github.com/QwikDev/qwik/pull/9010)
**fix(router): serve static files under the configured base path**

`base` を設定したときに静的ファイルも同じ場所を見に行くようにした修正。  
「本番だけ壊れる」系の友達です。

---

## 技術スタック（だいたい）

```text
Rust · TypeScript · Python
MCP / LLM 周辺 · Web まわりの小さなバグ修正
「動くものを先に出す」派（テストは後で…と言いがち）
```

---

## リンク

- GitHub: [KayanoLiam](https://github.com/KayanoLiam)
- ContextX: [github.com/KayanoLiam/ContextX](https://github.com/KayanoLiam/ContextX)
- X: [@kayano04kaoru](https://x.com/kayano04kaoru)

---

### 最後に

スターや Issue、PR のレビュー、どれも嬉しいです。  
ドキュメント修正でも、本番バグ修正でも、**マージされた瞬間の気持ちはだいたい同じ**です。

それでは、よいコーディングを 🍵
