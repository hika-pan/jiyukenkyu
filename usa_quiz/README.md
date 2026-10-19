# アメリカ基礎クイズ

50州と州都、地図上の位置、歴代大統領、歴史の年号を「覚える」「クイズ」の2モードで学ぶページ。

`index.html` をブラウザで開くだけで動く（ビルド不要）。

- `index.html` … ページ本体（データ・ロジック込み）
- `map-data.js` … 州の地図パス（データ: [us-atlas](https://github.com/topojson/us-atlas), ISC License）
- 大統領の肖像 … Wikimedia Commons から直接読み込む（下の出典を参照）

成績とタブの状態はブラウザの localStorage に保存される。

## 大統領の肖像の出典

すべて Wikimedia Commons の画像で、ライセンスはパブリックドメインまたは CC0。第24代は第22代と同じ画像を使う。

- 第1代 ジョージ・ワシントン: [Gilbert Stuart Williamstown Portrait of George Washington.jpg](https://commons.wikimedia.org/wiki/File:Gilbert_Stuart_Williamstown_Portrait_of_George_Washington.jpg)（Public domain）
- 第2代 ジョン・アダムズ: [Gilbert Stuart, John Adams, c. 1800-1815, NGA 42933.jpg](https://commons.wikimedia.org/wiki/File:Gilbert_Stuart,_John_Adams,_c._1800-1815,_NGA_42933.jpg)（CC0）
- 第3代 トーマス・ジェファーソン: [Official Presidential portrait of Thomas Jefferson (by Rembrandt Peale, 1800).jpg](https://commons.wikimedia.org/wiki/File:Official_Presidential_portrait_of_Thomas_Jefferson_(by_Rembrandt_Peale,_1800).jpg)（Public domain）
- 第4代 ジェームズ・マディソン: [James Madison.jpg](https://commons.wikimedia.org/wiki/File:James_Madison.jpg)（Public domain）
- 第5代 ジェームズ・モンロー: [James Monroe White House portrait 1819.jpg](https://commons.wikimedia.org/wiki/File:James_Monroe_White_House_portrait_1819.jpg)（Public domain）
- 第6代 ジョン・クインシー・アダムズ: [Portrait of John Quincy Adams (DRR) (Cropped).jpg](https://commons.wikimedia.org/wiki/File:Portrait_of_John_Quincy_Adams_(DRR)_(Cropped).jpg)（Public domain）
- 第7代 アンドリュー・ジャクソン: [Andrew jackson head.jpg](https://commons.wikimedia.org/wiki/File:Andrew_jackson_head.jpg)（Public domain）
- 第8代 マーティン・ヴァン・ビューレン: [Martin Van Buren circa 1837 crop.jpg](https://commons.wikimedia.org/wiki/File:Martin_Van_Buren_circa_1837_crop.jpg)（Public domain）
- 第9代 ウィリアム・ハリソン: [William Henry Harrison daguerreotype edit.jpg](https://commons.wikimedia.org/wiki/File:William_Henry_Harrison_daguerreotype_edit.jpg)（Public domain）
- 第10代 ジョン・タイラー: [WHOportTyler.jpg](https://commons.wikimedia.org/wiki/File:WHOportTyler.jpg)（Public domain）
- 第11代 ジェームズ・ポーク: [JKP.jpg](https://commons.wikimedia.org/wiki/File:JKP.jpg)（Public domain）
- 第12代 ザカリー・テイラー: [Zachary Taylor restored and cropped.jpg](https://commons.wikimedia.org/wiki/File:Zachary_Taylor_restored_and_cropped.jpg)（Public domain）
- 第13代 ミラード・フィルモア: [Millard Fillmore by Brady Studio 1855-65.jpg](https://commons.wikimedia.org/wiki/File:Millard_Fillmore_by_Brady_Studio_1855-65.jpg)（Public domain）
- 第14代 フランクリン・ピアース: [Mathew Brady - Franklin Pierce - alternate crop.jpg](https://commons.wikimedia.org/wiki/File:Mathew_Brady_-_Franklin_Pierce_-_alternate_crop.jpg)（Public domain）
- 第15代 ジェームズ・ブキャナン: [James Buchanan.jpg](https://commons.wikimedia.org/wiki/File:James_Buchanan.jpg)（Public domain）
- 第16代 エイブラハム・リンカーン: [Abraham Lincoln O-77 matte collodion print.jpg](https://commons.wikimedia.org/wiki/File:Abraham_Lincoln_O-77_matte_collodion_print.jpg)（Public domain）
- 第17代 アンドリュー・ジョンソン: [Andrew Johnson photo portrait head and shoulders, c1870-1880-Edit1.jpg](https://commons.wikimedia.org/wiki/File:Andrew_Johnson_photo_portrait_head_and_shoulders,_c1870-1880-Edit1.jpg)（Public domain）
- 第18代 ユリシーズ・グラント: [Ulysses S. Grant 1870-1880.jpg](https://commons.wikimedia.org/wiki/File:Ulysses_S._Grant_1870-1880.jpg)（Public domain）
- 第19代 ラザフォード・ヘイズ: [President Rutherford Hayes 1870 - 1880 Restored.jpg](https://commons.wikimedia.org/wiki/File:President_Rutherford_Hayes_1870_-_1880_Restored.jpg)（Public domain）
- 第20代 ジェームズ・ガーフィールド: [James Abram Garfield, photo portrait seated.jpg](https://commons.wikimedia.org/wiki/File:James_Abram_Garfield,_photo_portrait_seated.jpg)（Public domain）
- 第21代 チェスター・アーサー: [Chester Alan Arthur.jpg](https://commons.wikimedia.org/wiki/File:Chester_Alan_Arthur.jpg)（Public domain）
- 第22代 グロバー・クリーブランド: [Grover Cleveland - NARA - 518139 (cropped).jpg](https://commons.wikimedia.org/wiki/File:Grover_Cleveland_-_NARA_-_518139_(cropped).jpg)（Public domain）
- 第23代 ベンジャミン・ハリソン: [Benjamin Harrison, head and shoulders bw photo, 1896.jpg](https://commons.wikimedia.org/wiki/File:Benjamin_Harrison,_head_and_shoulders_bw_photo,_1896.jpg)（Public domain）
- 第25代 ウィリアム・マッキンリー: [Mckinley.jpg](https://commons.wikimedia.org/wiki/File:Mckinley.jpg)（Public domain）
- 第26代 セオドア・ルーズベルト: [Theodore Roosevelt by the Pach Bros (3x4 close cropped).jpg](https://commons.wikimedia.org/wiki/File:Theodore_Roosevelt_by_the_Pach_Bros_(3x4_close_cropped).jpg)（Public domain）
- 第27代 ウィリアム・タフト: [William Howard Taft, Bain bw photo portrait, 1908.jpg](https://commons.wikimedia.org/wiki/File:William_Howard_Taft,_Bain_bw_photo_portrait,_1908.jpg)（Public domain）
- 第28代 ウッドロウ・ウィルソン: [President Woodrow Wilson portrait December 2 1912.jpg](https://commons.wikimedia.org/wiki/File:President_Woodrow_Wilson_portrait_December_2_1912.jpg)（Public domain）
- 第29代 ウォレン・ハーディング: [Warren G Harding-Harris & Ewing.jpg](https://commons.wikimedia.org/wiki/File:Warren_G_Harding-Harris_%26_Ewing.jpg)（Public domain）
- 第30代 カルビン・クーリッジ: [Calvin Coolidge cph.3g10777 (cropped).jpg](https://commons.wikimedia.org/wiki/File:Calvin_Coolidge_cph.3g10777_(cropped).jpg)（Public domain）
- 第31代 ハーバート・フーヴァー: [President Hoover portrait.jpg](https://commons.wikimedia.org/wiki/File:President_Hoover_portrait.jpg)（Public domain）
- 第32代 フランクリン・ルーズベルト: [Franklin Roosevelt - Presidential portrait.jpg](https://commons.wikimedia.org/wiki/File:Franklin_Roosevelt_-_Presidential_portrait.jpg)（Public domain）
- 第33代 ハリー・トルーマン: [TRUMAN 58-766-06 (cropped).jpg](https://commons.wikimedia.org/wiki/File:TRUMAN_58-766-06_(cropped).jpg)（Public domain）
- 第34代 ドワイト・アイゼンハワー: [Dwight D. Eisenhower, official photo portrait, May 29, 1959.jpg](https://commons.wikimedia.org/wiki/File:Dwight_D._Eisenhower,_official_photo_portrait,_May_29,_1959.jpg)（Public domain）
- 第35代 ジョン・F・ケネディ: [John F. Kennedy, White House color photo portrait.jpg](https://commons.wikimedia.org/wiki/File:John_F._Kennedy,_White_House_color_photo_portrait.jpg)（Public domain）
- 第36代 リンドン・ジョンソン: [37 Lyndon Johnson 3x4.jpg](https://commons.wikimedia.org/wiki/File:37_Lyndon_Johnson_3x4.jpg)（Public domain）
- 第37代 リチャード・ニクソン: [Richard Nixon presidential portrait.jpg](https://commons.wikimedia.org/wiki/File:Richard_Nixon_presidential_portrait.jpg)（Public domain）
- 第38代 ジェラルド・フォード: [Gerald Ford presidential portrait (cropped).jpg](https://commons.wikimedia.org/wiki/File:Gerald_Ford_presidential_portrait_(cropped).jpg)（Public domain）
- 第39代 ジミー・カーター: [JimmyCarterPortrait2.jpg](https://commons.wikimedia.org/wiki/File:JimmyCarterPortrait2.jpg)（Public domain）
- 第40代 ロナルド・レーガン: [Official Portrait of President Reagan 1981.jpg](https://commons.wikimedia.org/wiki/File:Official_Portrait_of_President_Reagan_1981.jpg)（Public domain）
- 第41代 ジョージ・H・W・ブッシュ: [George H. W. Bush presidential portrait (cropped).jpg](https://commons.wikimedia.org/wiki/File:George_H._W._Bush_presidential_portrait_(cropped).jpg)（Public domain）
- 第42代 ビル・クリントン: [Bill Clinton.jpg](https://commons.wikimedia.org/wiki/File:Bill_Clinton.jpg)（Public domain）
- 第43代 ジョージ・W・ブッシュ: [George-W-Bush.jpeg](https://commons.wikimedia.org/wiki/File:George-W-Bush.jpeg)（Public domain）
- 第44代 バラク・オバマ: [President Barack Obama.jpg](https://commons.wikimedia.org/wiki/File:President_Barack_Obama.jpg)（Public domain）
- 第45代 ドナルド・トランプ: [Donald Trump official portrait.jpg](https://commons.wikimedia.org/wiki/File:Donald_Trump_official_portrait.jpg)（Public domain）
- 第46代 ジョー・バイデン: [Joe Biden presidential portrait.jpg](https://commons.wikimedia.org/wiki/File:Joe_Biden_presidential_portrait.jpg)（Public domain）
- 第47代 ドナルド・トランプ: [Official Presidential Portrait of President Donald J. Trump (2025).jpg](https://commons.wikimedia.org/wiki/File:Official_Presidential_Portrait_of_President_Donald_J._Trump_(2025).jpg)（Public domain）
