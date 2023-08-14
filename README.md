# Zenn Contents

[https://zenn.dev/ten_ten](https://zenn.dev/ten_ten)

✍🏻[How to use](https://zenn.dev/zenn/articles/zenn-cli-guide)

## Tips

GitHub で Zenn 記事を管理することに関連する公式記事

- [Zenn CLI をインストールする](https://zenn.dev/zenn/articles/install-zenn-cli)

- [Zenn CLI で記事・本を管理する方法](https://zenn.dev/zenn/articles/zenn-cli-guide)

- [GitHub リポジトリで Zenn のコンテンツを管理する](https://zenn.dev/zenn/articles/connect-to-github)

- [Zenn の Markdown 記法一覧](https://zenn.dev/zenn/articles/markdown-guide)

<br>

### コマンド

👇 新しい記事を作成する

```shell
$ zenn new:article

# オプション付
$ npx zenn new:article --slug 記事のスラッグ --title タイトル --type idea --emoji ✨
# slug はa-z0-9、ハイフン-、アンダースコア_の 12〜50 字の組み合わせにする必要がある
```

👇 新しい本を作成する

```shell
$ zenn new:book
```

👇 投稿をプレビューする

```shell
$ zenn preview
```
