## DjangoRestFrameworkに関する遺言状

- DjangoRestFrameWorkとは
- DjangoでAPIをさくっと作れる3rdパーティライブラリ
- ここでは *改めて基本的なことは書かない* ので数年間DRFに関わる中で得た知見についてつらつらとまとめていきたい.....
- restapiの思想みたいな話しもしません、どこかで本を読んでおいて下さい、基本rest的な思想に乗っかって書いていくつもりです

### 目次

- ぶっちゃけシリアライザーってなんなん？
- view(controller)の肥大化との戦い
- methodfieldは使うな！
- request用のserializer
- queryparam用のシリアライザー
- ModelSerializerの罠
- 普通のserializerを使う方が良い場面の方が多い
- requestを渡すな！
- nest=死


