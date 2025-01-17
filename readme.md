BVE5専用車両アドオン「東武鉄道10030/10050系」取扱説明書 - 17/10/01 03:00 -

------------------------------------------------------------------------------------------------------
この度はBVE用車両アドオン「東武鉄道10030/10050系」をダウンロードいただき、ありがとうございます。  
このテキストファイルには、使用上の注意が記載されていますので、必ずご一読ください。  

■1,注意事項  
このアドオンには一部実際の車両の挙動とは異なる部分があります。あらかじめご了承ください。  

また、このアドオンを使用したあらゆる損害において、私（Segtor）は一切の責任を負いかねます。  
ご使用は自己責任でお願いいたします。  

◆速度計が60km/hを指したまま動かない場合◆  
シナリオフォルダのパスに2バイト（全角）文字が入っているのが原因です。  
例えばシナリオフォルダの場所がデフォルトでユーザー名が日本語だと引っかかります。  
これは、Real Analog Gaugeプラグインの仕様によるものです。  
シナリオフォルダをCドライブ直下等の2バイト文字が含まれない場所へ移動してください。  

◆ファイル構造について◆  
前のバージョンからファイル構造が変わりましたので、上書きすると余分なファイルが残ります。  
不具合は出ないと思いますが、念のため前のバージョンを削除して新たに導入しなおして下さい。  
なお、以前に当データを車両指定していただいた路線データのシナリオファイルは書き換える必要があります。  
路線データの作者様方に置かれましては大変御面倒様では御座いますが記述の修正をお願い致します。  

◆動作環境について◆  
運転台の画像が表示されないという報告をいただいておりますが、  
当方の環境で正常に動作しているため原因の特定ができません。  
正常に動作を確認した環境の構成を記載しますので、ご参考ください。  

現在の製作環境  
OS	:Windows8.1 Pro (64bit)  
MB	:GIGABYTE H67A-D3H-B3  
CPU	:Intel Core i7-2600  
RAM	:12GB  
GPU	:AMD Radeon RX480  
VRAM	:8GB  

■2,アーカイブの内容  
車両指定の際は、"segtor"フォルダを"Bvets"フォルダに置き、シナリオファイルを以下の様に記述してください。  

＜共通＞  
VehicleTitle = 東武10030系  

◆駅名表示について◆  
本線の「業平橋」駅は「とうきょうスカイツリー」駅に、「松原団地」駅は「獨協大学前」駅に改称されました。  
「業平橋」駅だけを「とうきょうスカイツリー」駅に変えたい場合（2012年3月17日～2017年3月31日）は"_s"を、  
どちらも新駅名を表示したい場合（2017年4月1日～）は"_d"を、拡張子の直前に追加してください。  
※本線以外の車両は対応していません。　例：Vehicle = segtor\tobu10030\vehicle_hon_6t_d.txt  
 
＜本線＞  
・2両編成 モハ11230/50  
Vehicle = segtor\tobu10030\vehicle_hon_2m.txt  
・2両編成 クハ12230/50  
Vehicle = segtor\tobu10030\vehicle_hon_2t.txt  

・4両編成 クハ11430/50・クハ14430/50  
Vehicle = segtor\tobu10030\vehicle_hon_4.txt  
・4両編成 モハ11230/50  
Vehicle = segtor\tobu10030\vehicle_hon_4m.txt  
・4両編成 クハ12230/50  
Vehicle = segtor\tobu10030\vehicle_hon_4t.txt  

・6両編成 クハ11630/50・クハ11430/50  
Vehicle = segtor\tobu10030\vehicle_hon_6.txt  
・6両編成 モハ11230/50  
Vehicle = segtor\tobu10030\vehicle_hon_6m.txt  
・6両編成 クハ16630/50・クハ12230/50  
Vehicle = segtor\tobu10030\vehicle_hon_6t.txt  

・8両編成 クハ11630/50・クハ11430/50・クハ14430/50  
Vehicle = segtor\tobu10030\vehicle_hon_8.txt  
・8両編成 モハ11230/50  
Vehicle = segtor\tobu10030\vehicle_hon_8m.txt  
・8両編成 クハ12230/50・クハ16630/50  
Vehicle = segtor\tobu10030\vehicle_hon_8t.txt  

・10両編成 クハ11630/50・クハ11430/50・クハ14430/50  
Vehicle = segtor\tobu10030\vehicle_hon_10.txt  
・10両編成 モハ11230/50  
Vehicle = segtor\tobu10030\vehicle_hon_10m.txt  
・10両編成 クハ12230/50・クハ16630/50  
Vehicle = segtor\tobu10030\vehicle_hon_10t.txt  

＜野田線＞  
・6両編成 クハ11650  
Vehicle = segtor\tobu10030\vehicle_noda_6.txt  
・6両編成 クハ16650  
Vehicle = segtor\tobu10030\vehicle_noda_6t.txt  

＜東上線＞  
・4両編成 クハ11430/50・クハ14430/50  
Vehicle = segtor\tobu10030\vehicle_tojo_4.txt  

・6両編成 クハ11630/50  
Vehicle = segtor\tobu10030\vehicle_tojo_6.txt  
・6両編成 クハ16630/50  
Vehicle = segtor\tobu10030\vehicle_tojo_6t.txt  

・8両編成 クハ11430/50・クハ14430/50  
Vehicle = segtor\tobu10030\vehicle_tojo_8.txt  

・10両編成 クハ11630/50・クハ14430/50・クハ11030・クハ10030  
Vehicle = segtor\tobu10030\vehicle_tojo_10.txt  

■3,路線データ作者様向け情報  
ATSプラグインでサポートしている駅のほか、独自に定義した以下の駅名を表示できます。  

◆現在駅表示◆  
事業者10（東武）：東上線  
75　東武竹沢  
76　男衾  
77　鉢形  
78　玉淀  
79　寄居  

事業者20（西武）：越生線・野田線・伊勢崎線  
02　一本松   
03　西大家   
04　川角   
05　武州長瀬   
06　東毛呂   
07　武州唐沢   
08　越生  
09　大宮   
10　北大宮   
11　大宮公園   
12　大和田   
13　七里   
14　岩槻   
15　東岩槻   
16　豊春   
17　八木崎   
18　春日部   
19　藤の牛島   
20　南桜井   
21　川間   
22　七光台   
23　清水公園   
24　愛宕   
25　野田市   
26　梅郷   
27　運河   
28　江戸川台   
29　初石   
30　流山おおたかの森   
31　豊四季   
32　柏   
33　新柏   
34　増尾   
35　逆井   
36　高柳   
37　六実   
38　新鎌ヶ谷   
39　鎌ヶ谷   
40　馬込沢   
41　塚田   
42　新船橋   
43　船橋  
44　鷲宮   
45　花崎   
46　加須  
47　南羽生   
48　羽生  
49　川俣   
50　茂林寺前   
51　館林  
52　多々良   
53　県   
54　福居   
55　東武和泉   
56　足利市   
57　野州山辺   
58　韮川   
59　太田  
60　細谷   
61　木崎   
62　世良田   
63　境町   
64　剛志   
65　新伊勢崎   
66　伊勢崎   

事業者50（東急）：日光線・宇都宮線・鬼怒川線  
02　栗橋   
03　新古河   
04　柳生   
05　板倉東洋大前   
06　藤岡   
07　静和   
08　新大平下   
09　栃木   
10　新栃木   
11　合戦場   
12　家中   
13　東武金崎   
14　楡木   
15　樅山   
16　新鹿沼   
17　北鹿沼   
18　板荷   
19　下小代   
20　明神   
21　下今市   
22　上今市   
23　東武日光  
24　野州平川   
25　野州大塚   
26　壬生   
27　国谷   
28　おもちゃのまち   
29　安塚   
30　西川田   
31　江曽島   
32　南宇都宮   
33　東武宇都宮  
34　大谷向   
35　大桑   
36　新高徳   
37　小佐越   
38　東武ワールドスクウェア  
39　鬼怒川温泉   
40　鬼怒川公園   
41　新藤原  

◆行先表示◆  
20　たびじ  
21　上板橋  
22　武蔵嵐山  
23　坂戸  
24　越生  
25　曳舟  
26　草加  
27　伊勢崎  
28　越谷  
29　栃木  
30　東武日光  
31　東武宇都宮  
32　鬼怒川公園  
33　運河  
34　岩槻  
35　春日部  
36　大宮  
37　和光市  
38　船橋  
39　柏  
40　六実  
41　野田市  
42　清水公園  
43　七光台  
44　東岩槻  
45　北千住  
46　高柳  
47　林間学校  

◆Run音◆  
このアドオンのRun音は、以下の割り当てになっております。  

Run0	：バラスト(定尺レール)  
Run1	：バラスト(ロングレール)  
Run2	：鉄橋  
Run3	：トンネル  

■4,転載・転用について  
禁転載・転用です。車両指定は基本的に自由ですが、事後でも構いませんので  
メールかTwitterにてご連絡くださると、こちらからもリンクを貼らせていただきます。  

■5,Special Thanks!  

・高橋うさお様…  
「13号線共通型CS-ATCプラグイン」を使用させていただきました。  

・Commuter Train様…  
「クリスマスケーキセット」を使用させていただきました。  

・Rock_On様…  
「DetailManager」を使用させていただきました。  

・BVE Workshop様…  
「Real Analog Gauge」を使用させていただきました。  

この場を借りて、お礼申し上げます。ありがとうございました。  

■6,更新履歴  
2017/10/01　プラグインの不具合と対処法について注意事項を記述（アドオン本体に変更はありません）  
2017/09/30　プラグインの開発者モードが有効になったままだったのを修正  
2017/09/25　サウンド・画像の追加と削除・性能の修正・組成バリエーション追加・ファイル構造変更  
2014/03/01　プラグイン更新に対応し、ブザーと運転台を変更しました。  
2013/01/01　公開しました。  

------------------------------------------------------------------------------------------------------
2014/03/01　Segtor "4MB" Gelion（ http://segtor.web.fc2.com/ ）連絡先：segtor_tbtj＠yahoo.co.jp
