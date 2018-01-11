This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).  

---

## アイコン素材サイト:  
    http://flat-icon-design.com/  
    https://www.iconsdb.com/  

---

## 説明：  
このアプリはDOM操作がG1M(など)の上できちんと高速に動作することを  
検証し、デモとして閲覧することを目的に作られたアプリです。 

最初のページ(メインページ)にボタンが6つ表示され、それらのボタンのうち5つから  
各フォームに遷移するデモが流れます。  
ページは遷移しておらず、DOM要素の追加、削除のみでフォームが変わります。  
すべてのページに遷移し終わったのちに、待機時間がなく、高速で遷移するデモを流して、デモは終了します。  
メインページの6つのボタンの、更新ボタンを除いた、各ボタンを押下すると、  
デモを中断してそのボタンが表すアプリ画面になります。  
各アプリ画面からはメインページに戻れませんので、ブラウザでリロードしてください。  
更新ボタンを押下するとデモが最初から再生されます。  
CSSアニメーションはメインページにしか使用していません。  

1つ目のデモはslackのようなメッセンジャーアプリを想定したデモです。  
大量の要素を配置、表示したときに問題がないかをチェックする意味も兼ねています。  
左右のペインにはチャンネル、メモが各1000件表示され、  
真ん中のペインには2000件のメッセージが表示されます。  
これらはli、div、p要素などで構成されています。  

2つ目のデモは大量の画像を配置し、それらを選択するような、写真ビューアの  
ようなアプリを想定したデモです。  
大量の画像要素を配置、表示したときに問題がないかをチェックする意味も兼ねています。  
1種類のサンプル画像が1000件配置されます。  
これらはdiv、img要素などで構成されています。  

---

## コーディング・ビルド手順  
### 必要条件：  
Node >= 6   
### 手順：  
・このプロジェクトをクローンする  
・npm install create-react-app か npm install -g create-react-app を実行する  
・npm install を実行する  
・npm start を実行してコーディングする  
  この状態ではソースコードを更新すると即座に画面に反映されるので作業中は便利  
・npm run build でビルドする  
  これでビルドできる。  
