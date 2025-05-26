## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能

エンドポイント（APIのURL）https://zipcloud.ibsnet.co.jp/api/search

機能　郵便番号を指定して、その郵便番号に対応する住所（都道府県、市区町村、町域）を取得するAPI
* リクエストとレスポンスのフォーマット

HTTPメソッド：GET

パラメータ：zipcode：検索したい郵便番号
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL

名称：REST Countries API
参照URL：https://restcountries.com/
* エンドポイントと機能

エンドポイント：https://restcountries.com/v3.1/name/{name}?fullText=true

機能： 指定された国名（英語）に完全一致する国の情報を取得

取得できる情報には国名、首都、人口、地域（アジア、ヨーロッパなど）、通貨、国旗の画像URL
* リクエストとレスポンスのフォーマット

HTTPメソッド：GET

パラメータ：name：検索したい国名（英語、完全一致）

fullText=true：完全一致検索を指定
### Q3-3. 感想
* 今回の課題で苦労したこと
* 演習を通して理解できたこと
* Web APIの利便性や課題など
