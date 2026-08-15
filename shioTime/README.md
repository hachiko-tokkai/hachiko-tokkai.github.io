<h1>KNR-shioTime</h1>
俺が勝手に改造した古中鉄道向けshioTimeです。<br>
開発中のデータなので頻繁に変更があります。<br>
<br>
閲覧使用はこちらから→→<a href="https://digitalrtm.github.io/KNR-shioTime">digitalrtm.github.io</a><br>
通告txtの更新には1分程度要するので注意
<hr>
<h2>dia.jsonの作り方</h2>
1.上りダイヤ、下りダイヤをそれぞれouDiaのソフトでcsv出力する<br>
2.それぞれのcsvから"："(コロン)を全削除する<br>
3.oud2Shio.jsをNodeで実行する。上り、下の両方のcsvを読み込み、基準時刻は"2"とする<br>
4.出力されたjsonの、"group"のタイトルを正しく定義させる<br>
5."work"内にある運番と列番の定義ブロックを数字順に頑張って整列させる<br>
6.保存してアップする<br>
7.config.jsのDB一覧にダイヤを追加する<br>
多分これで終わり
