# doremi
string sound

```
//　スペースは区切りで、節の区切りで何もしない。
//０－９　テンポ変更。デフォルトは４。一小節は４文字で演奏される。
//ドレミフソラシ　//一文字、一音とするため、ファはフ
//｜　複数トラックとするための区切り文字
let track1=`
`

doremi(track1,loopnum)
doremi(track1+'｜'+track2,loopnum) //複数トラックとするには、｜で連結する。

```
