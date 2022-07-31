# 科技部計畫

## 統整資料
>* [年報95年-107年按產業分類](https://drive.google.com/drive/folders/1ipdht2cxK6MqARRlOGYjpdGy6tYS7dGH?fbclid=IwAR1xUNP1UUJV8gphvHgiegK5znUIod9IqpUpd_2xLAgoYlMmCZjLDJpuwA0)
>* [致股東報告書文本資訊與公司治理評鑑之關聯性研究](https://drive.google.com/drive/folders/1JtEiRvVbz-y5VW12Qy7dWfNxC7UIGj63?fbclid=IwAR1eWISX_yEcfKSNAaoAtNbxH1NqHghKyi-SdDJrPuHHLXK4uCxz4XzQUVg)
>* [致股東報告書文字資訊與裁罰案件關聯性之研究](https://drive.google.com/drive/folders/1ARhnjCUnABHp8nlWtDXM2XkY-m3k9oAl?fbclid=IwAR2i73K55mbcELavKIKQuBZWFTIQyK6eLIU5ioCoQ3oC7wQM5lYJgmHe5xw)
>* [公開觀測站](https://mops.twse.com.tw/mops/web/t57sb01_q5)
>* [上市公司代碼一覽](https://www.tej.com.tw/webtej/doc/uid.htm?fbclid=IwAR2R_sYXIvO2I75X7HCGzeJgkXiQb6Jme8KajNvl128s2VkCDBmXVhMCgRo)
>* [Notion](https://www.notion.so/fd77b1d4657041949d00d77dd3bd50af?v=c32de9689313428da76ff4de75046dcd)

## 程式碼使用說明

### 觀測站
>1. *年報爬取(下拉式選單*
>    * 依照電腦設定不同 *table.exe* 可能會造成自動化修改檔名有錯，請下載 *Autoit* 做修改
>    * [Autoit](https://www.796t.com/content/1544513614.html)
>
>1. *移動檔案*
>    * 將下載的檔案移到對應已有的資料夾
>
>1. 將 *本機端list*
>    * 找出結果不為pdf的檔案

### 辰瑜的論文
>1. 將所需至股東報告書放進資料夾
>
>1. 將至股東報告書放入 *頁碼部製作.ipynb*
>    1. 生成 *頁碼簿.xlsx*
>
>1. 將 *頁碼簿* 放入 *paragraph_seperator_v1(修改).ipynb*
>    * 生成 *頁碼簿_分段狀況.xlsx* (所有資料)
>    * 生成 *頁碼簿_分段結果.xlsx* (1~4段皆有的檔案)
>    
>1. 其他
>    * *paragraph_seperator_v1(原版).ipynb*
>    * *文字檔分段.ipynb*




## 預計目標
- [x] 8/23完成網頁製作並開好AWS的虛擬機
- [x] 9/6寫完資料爬蟲和複製雲端硬碟
- [x] 9/20補齊爬蟲防呆和複製雲端硬碟和練習BERT 
- [x] 11/1金融業BERT完成和寫餘弦歐式的程式
- [x] 1/13將頁碼簿進行修補與BERT程式更新
