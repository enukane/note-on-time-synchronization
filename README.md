# note-on-time-synchronization
「失われた時(時刻同期)を求めて "À la recherche du temps unsynchronisé"」 時刻同期に関するメモ

## なにか

「失われた時を求めて」 by プルースト のサブタイトルのぱくり

- 原子の輝線の方へ (原題: 「スワン家のほうへ」)
  - ルビジウム発信器の使い方
- 遮られた電波のかげに (原題：「花咲く乙女たちのかげに」)
  - GPS, 電波時計の電波到達性とavailabilityについて
- ワンセグのほう (原題：「ゲルマントのほう」)
  - yojiro さんのワンセグ時刻源話をベースに
    - ARIBひもとく
  - 実利用として取り込んでみる @キャプチャデバイス
  - pro et contra
    - GPS, 電波時計 <-> ワンセグ
    - 5秒間隔のところ？
- NTPとPTP (原題：「ソドムとゴモラ」)
  - IPでの標準プロトコル
- 囚われのRTC (原題：「囚われの女」）
  - HPET, RTCの機能、インタフェース、利用
  - OSにおける時間
- 逃げ去るクロック (原題：「消え去ったアルベルチーヌ」）
  - 時刻源から切り離されたHPET, RTCで生ずる誤差
  - 長期間の変動 (GPS等との比較をグラフ化)
- 見いだされた時 (原題：「見いだされた時」）
  - 時刻同期の選択について

## あるとうれしい内容

- モチベーション
  - wimpy & unnetworked node での利用
    - 環境: 電源、ネットワーク、利用シーン
    - 要求: packetへの時刻記録、複数台でのsync
- 時刻取得・同期の各手法
  - RTC
  - ルビジウム、原子時計
  - 電波時計
  - GPS
  - ワンセグ
  - 3G
  - NTP
  - PTP
- 手法の概要
  - 仕様
  - 実際の利用、実装
- 比較検討
  - pro et contra
    - 精度
    - 利用における制約
    - 実現・維持のコスト
    - availability
  - 実運用時の課題
    - 仕様としての制約 <-> 実際の結果
