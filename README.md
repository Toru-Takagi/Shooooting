# Shooooting
html canvasとjavascriptとNode.jsを組み合わせたリアルタイム協力シューティングゲーム  


##現在の進行状況
###サーバー側
expressも用いてhttp serverの作成→e71857b12ae85347076862518b71b924bf89d227  
プレイヤーの作成→ded3a86bcf48d3e78df761fb54ff15a50480f666  
プレイヤーの玉の作成→799cc4baf22ef5fc2bd355b4036638c765f46d08  
敵の作成→00a6f354fd6d18f3fc36eac427eb712cf302a6a6  
敵の種類を増やす→f295ee8616e69e952e04553804ac0c1bebbc2fad  
敵の玉の作成→53ef02d4f4e7300492b3082091e3c3a201dafd65  
プレイヤーの玉と敵のあたり判定→58ac07e0519dd8bc13700574e159eea3f57169cc  
敵の玉とプレイヤーのあたり判定  
敵と自分のあたり判定  
プレイヤーの体力の作成  
プレイヤーの玉の攻撃力の作成  
敵の体力の作成  
敵の玉の攻撃力の作成  
プレイヤーの体力が減る計算  
敵の体力が減る計算  
接続数２人以上を可能にする  
キャラの球をちゃんとする  
enemy.jsの当たり判定系をぐちゃぐちゃにしてしまったので直す  
ダブルバッファリングを行う  
接続解除したら、キャラクターを削除する  
接続人数の実装  
timerのオーバーフローを防ぐ  
接続数が０になったらclearInterval  
死んだら切断してゲームオーバーの表示  
ポイント機能の追加  
速度調整  
ポイントをファイルに書き込む  
ポイントの表示  
ランキング機能の実装  
玉の発射を５個までにする  
プレイヤー機に画像をつける  
敵機に画像をつける  
玉に画像をつける  
背景に画像をつける  

###クライアント側
基本的な物の作成→094636615d902fcb47dd450ed99b71b11317ea8d  
プレイヤーの描画→ded3a86bcf48d3e78df761fb54ff15a50480f666  
プレイヤーの玉の描画→799cc4baf22ef5fc2bd355b4036638c765f46d08  
敵の描画→00a6f354fd6d18f3fc36eac427eb712cf302a6a6  
敵の玉の描画→53ef02d4f4e7300492b3082091e3c3a201dafd65  

##今後の予定
###サーバー側
音をつける  
ランキングが微妙なのに、実験して正確か確かめる  
タイトル画面、ゲーム画面、結果画面と分ける  
CSVファイルなどを取得する機能を作る  

###クライアント側


###ゲームとして一応完成したら
ステージ１を作る(決まった敵が決まった動きをして降りてくる)  
当たり判定がガバガバだから直す  
敵ごとにちゃんと画像をつける  