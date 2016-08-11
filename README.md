# note-on-time-synchronization
「失われた時(時刻同期)を求めて "À la recherche du temps unsynchronisé"」 時刻同期に関するメモ

## なにか

「失われた時を求めて」 by プルースト のサブタイトルのぱくり

- 原子の輝線の方へ
- 遮られた電波のかげに
- ワンセグのほう
- NTPとPTP
- 囚われのRTC
- 逃げ去るクロック
- 見いだされた時

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
