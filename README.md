# person_msgs
  * topic通信とサービスの実装に使えるファイルで構成されたROS2パッケージです。
## Person.msg
  * string型の"name"とuint8型の"age"を送信する際に使えるファイルです。
## Query2.srv
  * uint8型の"birthmoon"を渡し、string型の"birthstone"を返すサービスに使えるファイルです。
# インストール
  * 当パッケージはROS2環境を前提としています。環境を用意したうえで以下を実行してください。
  ```
  $ cd ~/ros2_ws/src/
  $ git clone https://github.com/pl1-NT/person_msgs.git
  $ (cd .. && colcon build)
  $ source ~/.bashrc 
  ```
# ライセンス
  * このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます.
  * このパッケージのコードは下記のスライド(CC-BY-SA 4.0 by RyuichiUeda)のものを本人の許諾のもと一部改変、自身の著作としたものです。
　* [ryuichiueda/my_slides/robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022/ "利用したスライド")
  * © 2023 Touki Nishi
