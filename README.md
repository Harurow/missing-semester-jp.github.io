# The Missing Semester of Your CS Education (日本語版) [![Build Status](https://github.com/missing-semester-jp/missing-semester-jp.github.io/workflows/CI/badge.svg)](https://github.com/missing-semester-jp/missing-semester-jp.github.io/actions?query=workflow%3ACI)



[The Missing Semester of Your CS Education (日本語版)](https://missing-semester-jp.github.io/) のウェブサイトです！

本ページは[The Missing Semester of Your CS Education](https://github.com/missing-semester/missing-semester)を邦訳したものになります。

issues/PRによる貢献は歓迎です。実際に各セクションの翻訳を行いたい場合は次の手順に従ってください。

## How to translate
- 翻訳をしたい方は[@matsui528](https://github.com/matsui528)にgithubアカウントをお伝えください。
- [issues](https://github.com/missing-semester-jp/missing-semester-jp.github.io/issues)にて、翻訳対象のファイルごとにissueが立っています。closeされているものはもう翻訳が終わっています。対象のissueにて自分自身をassignしてください（更新が被ることを防ぐため）。ちなみにissueで既に誰かがassignされていた場合は既にその人が翻訳中です。
- ブランチを作り、翻訳を行い、PRを作ってください。PR中では上記issueをメンションしてください。


## Development

ローカルでビルドするには、次のコマンドを実行してください。

```bash
bundle exec jekyll serve -w
```

あるいは`docker`を使う場合は、以下のコマンドでビルドができます
```bash
docker run --rm --volume="$PWD:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll jekyll serve -w
```

## Translator
- [@matsui528](https://github.com/matsui528) (organizer)
- [@makotoshimazu](https://github.com/makotoshimazu) (organizer)
- [@take1108](https://github.com/take1108) (organizer)
- [@ikuehirata](https://github.com/ikuehirata) ([コマンドライン環境](https://missing-semester-jp.github.io/2020/command-line/), [講義ノート](https://github.com/missing-semester-jp/missing-semester-jp.github.io/blob/master/_2020/editors-notes.txt))
- [@soramichi](https://github.com/soramichi) ([メタプログラミング](https://missing-semester-jp.github.io/2020/metaprogramming/))
- [@logcpp](https://github.com/logcpp) ([シェルツールとスクリプト](https://missing-semester-jp.github.io/2020/shell-tools/))

## License

All the content in this course, including the website source code, lecture notes, exercises, and lecture videos is licensed under Attribution-NonCommercial-ShareAlike 4.0 International [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). See [here](https://missing.csail.mit.edu/license) for more information on contributions or translations.
