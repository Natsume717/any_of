# any_of
predicateのany_ofに関するデータパックサンプルになります。

詳しくはブログ記事『[【マイクラ】any_ofで複数条件から検知する【predicate】](https://natsumake.com/predicate_any_of/)』を参考にしてください。

<h3>使い方</h3>

導入後、スコアボードの値が画面横に出現します。<br>
現れない場合は```/reload```と入力し、実行してください。

```/execute if predicate sample:test run give @a diamond 1```を実行することで、any_ofが記述されているpredicate（test.json）を試すことができます。<br>
test.jsonの内容が真であれば、ダイヤモンドが付与され、条件を満たしていない場合はダイヤモンドが付与されません。
