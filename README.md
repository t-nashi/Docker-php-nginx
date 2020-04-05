# Docker-php-nginx
Docker で php を実行できる webサーバー（nginx）を準備
<br><br><br>



## 使用法 （Usage）

1. このページの `Clone or download` ボタンよりリポジトリのクローンもしくはZIPダウンロード
2. ZIPダウンロードの場合は解凍
3. 解凍して出来たフォルダをDockerコマンドが有効な場所に置く
4. コマンドプロンプト（win）/ ターミナル（mac）を起動し、「3」のフォルダ内へ移動
5. `docker-compose up -d` コマンドを実行（しばらくインストールが走る）
6. ブラウザからwebサーバーアクセスを確認 → http://localhost:8080/
7. ブラウザからwebサーバーアクセス＆php実行を確認 → http://localhost:8080/index.php
8. ブラウザからwebサーバーアクセス＆phpinfo確認 → http://localhost:8080/info.php
<br><br><br>



## コマンド一覧

<table>
 <tr>
 	<td><b>$ docker version<br>$ docker -v</b></td>
  <td>Docker のバージョン確認</td>
 </tr>
 <tr>
  <td><b>$ docker-compose version<br>$ docker-compose -v</b></td>
  <td>docker-compose のバージョン確認</td>
 </tr>
 <tr>
  <td><b>$ docker-machine version<br>$ docker-machine -v</b></td>
  <td>docker-machine のバージョン確認</td>
</tr>
</table>  
<br>


<table>
<tr>
  <td><b>$ docker-compose up -d</b></td>
  <td>コンテナの作成と開始</td>
 </tr>
 <tr>
  <td><b>$ docker-compose ps</b></td>
  <td>起動中のコンテナ一覧表示（docker-compose）</td>
 </tr>
 <tr>
  <td><b>$ docker ps</b></td>
  <td>起動中のコンテナ一覧表示（docker）</td>
 </tr>
 <tr>
  <td><b>$ docker ps -a</b></td>
  <td>起動してないものも含む全てのコンテナ一覧表示 （docker）</td>
 </tr>
 <tr>
  <td><b>$ docker rm xxxxx</b></td>
  <td>コンテナの削除 （docker）</td>
 </tr>
</table>  
<br>


<table>
<tr>
  <td><b>$ docker images</b></td>
  <td>イメージ一覧 （docker）</td>
 </tr>
 <tr>
  <td><b>$ docker rmi xxxxx</b></td>
  <td>イメージの削除 （docker）</td>
 </tr>
 <tr>
  <td><b>$ docker rmi xxxxx -f</b></td>
  <td>強制的なイメージの削除 （docker）</td>
 </tr>
</table>  
<br>


<table>
<tr>
  <td><b>$ docker stop</b></td>
  <td>サービスの停止</td>
 </tr>
 <tr>
  <td><b>$ docker down</b></td>
  <td>コンテナの停止</td>
 </tr>
</table>  
<br><br><br>

