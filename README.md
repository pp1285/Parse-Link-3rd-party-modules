# Parse-Link-3rd-party-modules
now I link facebook
https://github.com/ParsePlatform/parse-server/wiki/Parse-Server-Guide
server在heroku然後db在mongolab
然後我看到上面那個教學有第三方auth的教學，就想說用facebook來連連看，
我有兩個server，一個的index.js有facebookID，一個沒有
兩個都用facebook 帳號登入
結果兩個都可以跟db溝通，都可以寫入新註冊的使用者
我的天啊～
那這樣我還要第三方auth教學幹嘛？

# 3/18更新-結論
oauth如果hide起來的時候呢，我猜有個cache把它存起來了，</br>
那如果今天呢，我們把oauth的facebookID換成另一個app，就會出現error囉～
所以oauth還是必須存在的～
