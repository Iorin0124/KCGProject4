----------階層構造と内容物について----------
CelestialBodyInThePalm
	css
		*.css		//プロジェクトで使用している自作css
		bootstrap*.css		//HTML系フレームワークBootstrapによるcss
		drawer.min.css		//ハンバーガーメニューdrawerプラグインによるcss
	img
		*.jip		//プロジェクトで使用しているjpeg画像
		*.png		//プロジェクトで使用しているpng画像
	js
		bootstrap**.js		//HTML系フレームワークBootstrapによるjs
		drawer.min.js		//ハンバーガーメニューdrawerプラグインによるjs
		iscroll.js		//ハンバーガーメニューiscrollプラグインによるjs
		jquery-3.1.1.min.js		//jQueryプラグイン
		OrbitControls.js		//WebGLのプラグインthree.jsによるカメラ制御用のjs
		planet_information.js		//各惑星ページで情報を表示させる為の自作js
		TDSLoader.js		//WebGLのプラグインthree.jsによるモデル読み込み用のjs
		three.min.js		//WebGLのプラグインによるjs
	textures
		*.jpg		//各惑星のテクスチャ　NASAから取得後、3DCG用に加工又は完全自作のもの
	
	(惑星名).html	//その惑星の3DCGオブジェクトを表示させたページ
	solar_system.html	//太陽系全体の3DCGオブジェクトを表示させたページ
	(惑星名)_infomation.html	//その惑星の情報を表示させたページ
	solar_system_infomation.html	//太陽系全体の情報を表示させたページ
	*.html		//その他Webサイトを構成するページ

----------ビルド手順----------
zip圧縮されたCelestialBodyInThePalmを全て解凍し、Webサーバ上で起動してください。
準備はたったそれだけです。

----------注意事項----------
・階層構造は変えないでください。正しく動かなくなります。
・WebGLのサポートが一部のAndroid，iOS端末の最新バージョンまで行き届いていない場合があります。こちらはWebGL側のアップデート待ちです。