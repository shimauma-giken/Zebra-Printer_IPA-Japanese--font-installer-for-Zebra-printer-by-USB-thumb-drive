# Zebra-Printer_IPA-Japanese--font-installer-for-Zebra-printer-by-USB-thumb-drive
IPA font installer for Zebra printer by USB thumb drive.

Following the guides below to install IPA Mincho and Gothic fonts to Zebra printer and print sample label. 

# What you will need
- Zebra printer which can insert USB flash drive.
- USB flash drive 

# How to guides
1. Format USB flash drives with FAT32.
2. Download "Zebra folder" and copy it to root of USB flash drive. 
3. Insert USB flash drive to printer. Install process should start and reboot the printer. 
4. Send "print_ipa.zpl" to the printer. It should print 2 types of Japanese font, Mincho and Gothic, printed as below.
   - IPA Gothic 日本語
   - IPA Mincho 日本語

* Please note that installed fonts will be only supported by ZPL. 

   --------
   
 # ゼブラプリンタにIPA 明朝/ゴシックフォントをインストールする方法 (USB-Mirrorを利用)  
   
 # 用意すべきもの
 - Zebra プリンタ、USBメモリに対応し
 - USBメモリ
 
 # インストール手順
 1. USBメモリをFat32形式でフォーマットする。
 2. Zebra フォルダをダウンロードする（※１）。解凍が必要であれば解凍する。Zebra フォルダをUSBメモリのルートディレクトリにコピーする。
 3. USBメモリをプリンタに挿す。ミラー処理が開始し、プリンタは再起動する。
 4. "print_ipa.zpl" をプリンタに送付する。IPA 明朝とゴシックが印刷される。
 
 ※１、本画面の右上「Code▼」→ 「Download ZIP」を選択  
 
     
    
 # ゼブラプリンタにIPA 明朝/ゴシックフォントをインストールする方法 (ZebraNet Bridgeを利用)  
   
 # 用意すべきもの
 - ZebraNet Bridgeソフト
 - USBケーブル（プリンタに合ったもの）
 
 # インストール手順 (IPA Gothicの場合）  
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

 4. 作成した"xxxxx.zpl" をプリンタに送付する。
 5. テスト印字をし、IPA Gothicの印刷を確認する。
 
 ※１、本画面の右上「Code▼」→ 「Download ZIP」を選択
