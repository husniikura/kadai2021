# 2021年度プログラミング基礎の課題

## 課題一覧

1. 課題1  99 Bottles of Beer on the Wall
   - [kadai1の説明](kadai1)
   - https://github.com/husniikura/kadai2021-1
2. 課題2  Bubble Sort
   - [kadai2の説明](kadai2)
   - https://github.com/husniikura/kadai2021-2
3. 課題3  電卓アプリ
   - [kadai3の説明](kadai3)
   - https://github.com/husniikura/kadai2021-3
4. 課題4  アプリの自由製作
   - [kadai4の説明](kadai4)
   - https://github.com/husniikura/kadai2021-4

## マニュアル

- 以下のマニュアルに従って、設定してください。
  - [設定マニュアル](manual.md)

## 提出方法
次の手順で提出してください。
1. 課題一覧の各種リポジトリを `フォーク` してください
2. フォークしたリポジトリを `クローン` してください
3. 課題を解答し、 `コミット` ＆ `プッシュ` してください
4. Githubの画面から `Pull Request(PR)` を作成してください

### 提出例
課題は `kadai2021-1` とします。
ユーザー名は `xxxuser` とします。

1. Chromeにて下記のアドレスを開きます。
    https://github.com/husniikura/kadai2021-1
    開いたら、右上の `Fork` ボタンをクリックします。
    フォークが成功すると、URLが
    https://github.com/xxxuser/kadai2021-1
    に変わります。
2. VS Code にてリポジトリのクローンを実行します。
    - 新規のリポジトリを開く必要がありますので、上部のメニューから
        File > New Window
        を選択します。
    - 左側のメニューから「ソース管理」を選択し、「リポジトリのクローン」を選択します。
    - 上のダイアログから `github から複製` を選択します。
    - ダイアログやブラウザで確認画面が表示されますので、一つずつ許可します。
    - リポジトリ名の一覧の中から xxxuser/kadai2021-1.git を選択します。
3. 課題を解答します。
    - 解答方法は2通りがあり、どちらの方法でも構いません。
        1. Chrome のディベロッパーツールのコンソールに貼り付けたら動作する JavaScript ファイル1つを作成する。
        2. HTMLファイルとJavaScriptファイルを組み合わせて、HTMLファイルを開いたときに自動的にプログラムが動作するようにする。
    - 解答したら、VS Codeのソース管理画面からコミットします。
    - コミットできたら、VS Codeの左下のアイコンに数字が表示されます。
    - 表示された数字の部分はボタンになっているので、それをクリックするとプッシュされます。
        - プッシュが失敗する場合は、 [git pushの方法](git-pushの方法.md) を確認してください。
4. Github で当該リポジトリを開きます。
    https://github.com/xxxuser/kadai2021-1
    - メニューから `Pull requests` を選択します。
    - `New pull request` をクリックします。
    - `←` の左側は `husniikura/kadai2021-1`, `base: main` のままにしてください。
    - `←` の右側は `xxxuser/kadai2021-1`, `compare: main` のままにしてください。
    - `Create pull request` ボタンをクリックします。
    - タイトルには `学籍番号` を入れます。
    - 右下の `Create pull request` ボタンをクリックします。

以上で提出が完了となります。
PRの作成が完了すると、
https://github.com/husniikura/kadai2021-1/pull/NN (`NN`: 連番)
に移動します。 `husniikura` のリポジトリに移動していますのでご注意ください。
`Pull request` をクリックしますと他の学生が作成したPRも閲覧可能です。
こちらにつきましては見ていただいて構いません。

## 採点方法
- Pull Request(PR) を受け付けた時点から、順次コメントを付けます。
- 改善が必要なもの、あるいは要求を満たさないものにつきましては、修正を求めるコメントを付けます。
- 修正を求めるコメントが付きましたら、これに対応してください。
- 対応が完了したら `コミット` & `プッシュ` してください。自動的にPRが更新されます。
- 要件を満たしているかどうかを 60点満点 で評価します。
- 技術的な要件を満たしているかどうかを 40点満点 で評価します。
- 採点結果の得点は Moodle に記載しますが、PRのコメント作成時点と評価時点との間には時間的なズレがあります。
