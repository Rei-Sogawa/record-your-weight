# メモ

## 仕様

- 体重を入力できる

  - xx.xx [kg]

- グラフ化できる

## タスク

- record type を作る

  - id
  - kilogram
  - createdAt

- 入力フォームを作る

  - テキストインプット
    - xx.xx で validation
  - サブミットボタン

- グラフを表示する

  - 横軸が createdAt
    - ちょっと難しそう。とりあえずは下参考にする
    - <https://absarcs.info/how-to/react-recharts-axis-datetime/>
  - 縦軸が kilogram
    - 範囲は 60 ~ 80 にする

- redux のアクションを作る

  - fetchRecords
  - addRecord
  - deleteRecord

- 永続化はとりあえず local storage にする
