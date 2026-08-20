ブラウザで動作する音響カプラです。<br>
2台の端末のマイクとスピーカーで文字列の送受信ができます。<br>
特に決まりはないのでアルファベットの他に日本語でも通信できます。<br>
受信に失敗する場合はマイクのボリュームを上げてください。<br>
周りの環境音が多い場合はノイズに埋もれて通信エラーになります。<br>
それでも通信エラーになる場合は以下の周波数を変更してください。<br>
const START_FREQ=800;<br>
const STOP_FREQ=900;<br>
const BIT0=1200;<br>
const BIT1=2200;<br>
const RX_HIGH_PASS_FREQ=750;<br>
const RX_LOW_PASS_FREQ=2800;<br>
<br>
サンプルページ<br>
<a href="https://shizukaya.github.io/AcousticCoupler/AcousticCoupler.html">AcousticCoupler</a>
