# 2014utasp
アンケート回答から政治家の所属政党を機械学習で予測できるかの研究

東京大学谷口研究室・朝日新聞社共同調査  
2014年衆院選候補者調査  
http://www.masaki.j.u-tokyo.ac.jp/utas/utasp.html  
配布されているcsvファイルから2014UTASP.csvを作成  
作成にあたって
* NAME, PARTY, Q6_1-Q8, Q9-Q13の列を抜粋
* 有効回答行を抜粋
* 自, 民, 維, 公, 次, 共政党議員を抜粋
* 無回答(99)を(6)または(5)に変換  
1000人分のデータとなった。

