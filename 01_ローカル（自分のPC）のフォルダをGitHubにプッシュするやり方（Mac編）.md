# ローカル（自分のPC）のフォルダをGitHubにプッシュするやり方（Mac編）

## 手順
1. リモートリポジトリを作成する
2. 自分のPCのフォルダをローカルリポジトリに追加する
3. 手順1で作成したリモートリポジトリと手順2で作成したローカルリポジトリを接続する
4. addする
5. commitする
6. pushする

### 1. リモートリポジトリを作成する
1. 以下のURLにアクセスする。ログインがまだの場合ログインもする。  
リモートリポジトリを作成する  
https://github.com/

2. 右上の「＋」アイコンをクリックし、「New repository」をクリックする
  ![画像](./img/top.png)

3. リポジトリ名を入力し、 「Create repository」をクリックする
  ![画像](./img/new_repository.png)

4. 以下のような画面が表示されればOKです
  ![画像](./img/finish_create_repository.png)

### 2. 自分のPCのフォルダをローカルリポジトリに追加する
1. SourceTreeを開き、「新規」→既存のローカルリポジトリを追加をクリックする
  ![画像](./img/add_local_repository.png)

2. GitHubに上げたいフォルダを選択し、「開く」をクリックする
  ![画像](./img/select_local_folder.png)

3. GitHubに上げたいフォルダを選択し、「開く」をクリックする
  ![画像](./img/create_local_repository.png)

4. 作成されたローカルリポジトリをクリックする
  ![画像](./img/select_created_local_repository.png)

5. 以下のような画面が表示されればOK
  ![画像](./img/sourcetree.png)

### 3. 手順1で作成したリモートリポジトリと手順2で作成したローカルリポジトリを接続する
1. 設定アイコンをクリックする
  ![画像](./img/click_setting.png)

2. リモートを選択し、「追加」をクリックする
  ![画像](./img/select_remote.png)

3. リモート名に「origin」と入力する。  
URL / パスには手順1で作成したリモートリポジトリのURLGitHub取得し、貼り付ける。  
入力できたら「OK」をクリックする。
  ![画像](./img/input_setting.png)
  ![画像](./img/repository_url.png)

4. リモートリポジトリが追加されていることを確認し、「OK」をクリックする
  ![画像](./img/added_remote.png)

### 4. addする
1. 「ステージングに未登録のファイル」チェックボックスをクリックし、**add**する。
  ![画像](./img/add.png)

### 5. commitする
1. コミットメッセージを入力し、**commit**する。
  ![画像](./img/commit.png)

### 6. pushする
1. プッシュアイコンをクリックする
  ![画像](./img/push01.png)

2. masterをクリックし、「OK」をクリックする
  ![画像](./img/push02.png)

3. pushが完了したら、GitHubのページに行き、pushしたファイルが追加されていることを確認する
  ![画像](./img/push03.png)