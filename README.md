# CheckWeatherInfo
現在と過去の天気情報を気象庁のデータから取得して表示する

# 要件
- 現在地もしくは指定の地域の現在の天気に関すると予報、過去（1年前、2年前の前後1week）の情報を一画面に表示する。
- 天気の情報は毎日の農作業をスムーズにする事を目的にする。

# 技術
- URL転送ライブラリ。これを使って目的の情報を含むWebSiteのソースを取得し解析する。
　cURL　https://ja.wikipedia.org/wiki/CURL
- WebSiteのパース。
　XmlPullParser https://developer.android.com/reference/org/xmlpull/v1/XmlPullParser.html
 
