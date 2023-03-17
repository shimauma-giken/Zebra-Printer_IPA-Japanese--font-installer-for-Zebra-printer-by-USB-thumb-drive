 
 ## ゼブラプリンタにIPA 明朝/ゴシックフォントをインストールする方法 (USB-Mirrorを利用)  
   
 ## 用意すべきもの
 - Zebra プリンタ、USBメモリに対応し
 - USBメモリ  
    
 
 ## インストール手順
 1. USBメモリをFat32形式でフォーマットする。
 2. Zebra フォルダをダウンロードする（※１）。解凍が必要であれば解凍する。Zebra フォルダをUSBメモリのルートディレクトリにコピーする。
 3. USBメモリをプリンタに挿す。ミラー処理が開始し、プリンタは再起動する。
 5. テスト印字をし、IPA Gothicの印刷を確認する。  
 
     
   
   --------
   
     
     
    
 ## ゼブラプリンタにIPA 明朝/ゴシックフォントをインストールする方法 (ZebraNet Bridgeを利用)  
     
     
 ## 用意すべきもの
 - ZebraNet Bridgeソフト
 - USBケーブル（プリンタに合ったもの）
   
   
 ## インストール手順   
 1. ZebraNet Bridge for Enterprise(以下ZNB)をダウンロードし、Windows PCにインストールする。  
 　　https://www.zebra.com/jp/ja/support-downloads/printer-software/zebranet-bridge-enterprise.html  
 2. IPA Font*をダウンロードする。 
 <pre>
    * TTF形式のフォントのみサポートしています。
    * 3rd パーティ製フォントのご利用はZebra社のサポート対象外となりますので、動作検証の上でご利用ください。
 </pre>
 3. 「ZNBを起動 > ツール > フォントウィザード」を実行し、フォントインストーラを作成する。
 　　
 　　![image](https://user-images.githubusercontent.com/111269302/225861512-4cc75e1e-fc56-4416-aa0e-a0aca64b9c06.png)
   
   * 詳細は下記リンクを参照すること。  
   https://support.zebra.com/cpws/docs/inquira/attachments/SO8535.pdf  

 4. PC上に作成された"xxxxx.zpl" をプリンタにZSU等を利用してファイル送信する。
 5. テスト印字をし、IPA Gothicの印刷を確認する。  
