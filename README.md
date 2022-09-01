# IMU6050
単なる動作確認用プログラムです。多くの思い違いや明らかなミスなどあるかと思います。
参考程度でご利用ください。

（１）program：MPU6050による姿勢の検出を行う。主にC言語

Madgwick Filterへのサンプリング周波数の受渡（Madgwick.cの一部改変含む）。	
サンプリング周期の計測を入れた。 
青ボタンによる割込み処理でGyroのオフセットの補正。 
描画ソフトprocessingへのデータ出力。

（２）Accel_PostureQuaternion_NewV2：　processingでの描画プログラム
　ジャイロセンサの姿勢とその時の加速度センサの出力を表示する。 
 
（３）Rotation_shuttleXYZ： processingでの描画プログラム
　MPU6050からのデータをTeraterm経由で受信し、shuttleを回転する。
 
 （４）Mdgwic4PushButton_final2。pdf
 
 プログラムの説明メモ。
 
 
 以上
