# Learn Lefthook

## 本リポジトリの目的
[Husky](https://github.com/typicode/husky)と[lint-staged](https://github.com/lint-staged/lint-staged)のまとめたようなGitフック管理ツール『[Lefthook](https://github.com/evilmartians/lefthook)』を使って、無料で手軽にmainブランチへの直プッシュを抑止したい  
ついでに、daxとBun Shellの機能も見たい

## 本リポジトリの達成目標
- [ ] Lefthookでgit push時にブランチ名をログに出すように実装
- [ ] ブランチ名がmainのときにgit pushをエラーにするよう修正
- [ ] 上記をBun Shellで再実装

## 参考資料
- [[GitHub] ブランチの保護設定を活用しよう 【レビューが通るまでマージさせんぞ】 | DevelopersIO](https://dev.classmethod.jp/articles/protect-branch)
- [ブランチ保護ルールを管理する - GitHub Docs](https://docs.github.com/ja/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/managing-a-branch-protection-rule)
- [Git Hooks | Biome](https://biomejs.dev/ja/recipes/git-hooks)
- [$ Shell – API | Bun Docs](https://bun.sh/docs/runtime/shell)
- [Git フック管理ツール「Lefthook」の紹介](https://zenn.dev/sukesan0720/articles/87a8c005f82522)
- [husky + lint-stagedの支配から解放されるLefthookという選択肢 #Git - Qiita](https://qiita.com/yug1224/items/04fcda46544ddd05919d)
- [husky+lint-stagedからlefthookに乗り換えたので違いとか使えそうな設定とかまとめる](https://zenn.dev/kimuson/articles/husky_to_lefthook)
- [daxはいいぞ](https://zenn.dev/hashrock/articles/5dae2e171533a6)
