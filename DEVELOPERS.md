# Developing

* [コミットメッセージ記述規約](#commits)
* [参考URL](#references)

### コミットメッセージの書き方
1行あたりのコメントは100文字以内

```
1行目：Prefix変更内容の要約（タイトル、概要）
2行目 ：空行
3行目以降：変更した理由（内容、詳細）
```

### Revert
If the commit reverts a previous commit, it should begin with `revert: `, followed by the header
of the reverted commit.
In the body it should say: `This reverts commit <hash>.`, where the hash is the SHA of the commit
being reverted.
A commit with this format is automatically created by the [`git revert`][git-revert] command.

### Prefix
Must be one of the following:

* **feat**: 新機能
* **fix**: バグ修正
* **docs**: ドキュメンテーションのみ修正
* **style**: 動作に影響を与えない修正（例：フォーマット 等）
* **refactor**: バグ修正や新機能追加以外のコード修正
* **perf**: パフォーマンス向上の為のコード修正
* **test**: テストコードに関する修正
* **chore**: ビルド設定やライブラリ、補助ツール（例：ドキュメント生成 等）などの修正

### 参考URL
[Developing AngularJS]: https://github.com/angular/angular.js/edit/master/DEVELOPERS.md/
[Gitのコミットメッセージの書き方]: https://qiita.com/itosho/items/9565c6ad2ffc24c09364
