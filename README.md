# my-java-formatter
Eclipse で Java 開発をする時に使うフォーマッター。  
フォーマッター「Eclipse [ビルトイン] 」をベースに作成。

## こだわりポイント
- インデントは **空白スペース4つ**
- switch文の case でインデントを増やす
- **行の最大幅は 150**
- **折り返された行のインデントは空白スペース2つ**
- 折り返された配列イニシャライザのインデントは空白スペース4つ
- 「コメント」を結合しない（改行を維持させる）
- **コメントのブランク行を除去**
- **JavaDoc の「名前」「説明」の開始位置を揃える**
