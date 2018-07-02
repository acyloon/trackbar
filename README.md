# トラックバーを用いた画像処理
OpenCVを使ってトラックバーを付けた．
そこからパラメータを調節し，リアルタイムで動画を画像処理する．

# RGB色調変更

R(赤),G(緑),B(青)のトラックバーを動かすことでそれぞれの色味を調節できる．

# 明度調節 

gammaのトラックバーを動かすことで明るさを調節できる．

# ガウシアンフィルタリング

gaussianを1にすることで開始．

filter_heightでフィルタの高さ，filter_widthでフィルタの幅，sigmaで分散値を変更できる．

# リセット機能

resetを1にすることで全パラメータを初期値に戻すことができる．

# 実際に動かしてみた様子

<https://www.youtube.com/watch?v=lmVZDZMRA10&feature=youtu.be>

# 参考文献

<http://rasp.hateblo.jp/entry/2016/01/24/214027>

<https://qiita.com/hitomatagi/items/12a2eceaf65f142ec3df>

<https://qiita.com/Kazuhito/items/c43e96ab16f400a35721>

<https://algorithm.joho.info/programming/python/opencv-gaussian-filter-py/>
