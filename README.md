# サーバレッスン
Linuxプラクティス
-----------------
mkdir server_lesson $$ cd server_lesson
git init
touch first.txt
mkdir -p server_lesson/linux_practice/public
ls server_lesson server_lesson/linux_practice
touch server_lesson/linux_practice/public/index.php
cd /vagrant/server_lesson $$ ls
cp incex.php index_bk.php
cp -r public tmp
mv server_lesson/linux_practice server_lesson/linux_practice1
rm *_bk.php
rm -r linux_practice3
echo '# サーバレッスン' > README.md
echo 'Linuxプラクティス' >> README.md
echo '-----------------' >> README.md
vi README.md

