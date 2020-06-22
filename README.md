# 3d-reversi
3Dで遊べるリバーシ(オセロ)です

デモはこちら  
https://kt-watson.github.io/3d-reversi/app/

# 起動方法
```
git clone https://github.com/kt-watson/3d-reversi.git

cd 3d-reversi/app

sudo docker run -it -v $PWD:/workdir -p 8080:8080 node bash

cd /workdir

npm install

npm start

//ブラウザでlocalhost:8080にアクセス
