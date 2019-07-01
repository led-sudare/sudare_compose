LED-SUDARE Docker compose
===
LED-SUDARE関連サービスを1ホスト上で動作させます。

# Get Started🏁

1. Get srcs
```sh
mkdir LED-SUDARE
cd LED-SUDARE
git clone https://github.com/led-sudare/3d_led_cube_adapter.git
git clone https://github.com/led-sudare/3d_led_cube_go.git
git clone https://github.com/led-sudare/audigo-sdl.git
git clone https://github.com/led-sudare/mori_adapter.git
git clone https://github.com/led-sudare/mori_ledcube.git
git clone https://github.com/led-sudare/simulator.git
git clone https://github.com/led-sudare/sudare_compose.git
git clone https://github.com/led-sudare/sudare_contents.git
git clone https://github.com/led-sudare/xpub_xsub_proxy.git
```

2. Deploy
```sh
cd sudare_compose
docker-compose up -d
```

3. Access
ブラウザで以下のURLを開く  
[Simulator](http://localhost:2345)  


