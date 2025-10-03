# 📘 Aliexpress-Scraping

<p align="center">
  <img src="https://github.com/Ekans111/Aliexpress-Scraping/blob/master/img/interface.jpg?raw=true" alt="interface" />
</p>

---

## 🌍 Description / 説明

**EN:**  
This project is a web scraper built using **Selenium** to extract data from **AliExpress**.  
It supports scraping from **Product pages** and **Store pages**.

**JP（日本語）:**  
このプロジェクトは **Selenium** を使用して **AliExpress** からデータを抽出するための Web スクレイパーです。  
**商品ページ** および **ストアページ** のスクレイピングに対応しています。  

---

## ⚙️ Prerequisites / 前提条件

- Python 3.10.9  
- Selenium  
- Chrome WebDriver  

---

## 📥 Installation / インストール

**EN:**
1. Clone this repository.  
2. Install the required dependencies:  

```bash
pip install -r requirements.txt
```

**JP（日本語）:**  
1. このリポジトリをクローンします。  
2. 必要な依存関係をインストールします:  

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage / 使い方

**EN:**
1. Add the URLs you want to scrape into the file `URL.csv`. Example:

   ```
   https://ja.aliexpress.com/item/33060691049.html?spm=a2g0o.best.moretolove.17.440b1fd3hyIIjK&gatewayAdapt=glo2jpn
   https://ja.aliexpress.com/store/4997284/pages/all-items.html?sortType=bestmatch_sort&shop_sortType=bestmatch_sort
   ```

2. Run the script:  
   ```bash
   py main.py
   ```

3. Enter the **NG words** (comma-separated). Items containing one of these words in the name will be ignored.  

4. Click the **「開始」** button.  

5. When Chrome browser opens, change the currency to **JPY** (the scraper is designed for Japanese).  

6. Wait until the message “process done” appears, then click **「終了」**.  

7. Results will be saved to `登録.csv`.  
   - Downloaded images are stored in the `result` folder.  

---

**JP（日本語）:**  
1. スクレイプしたいURLを `URL.csv` に追加してください。例：  

   ```
   https://ja.aliexpress.com/item/33060691049.html?spm=a2g0o.best.moretolove.17.440b1fd3hyIIjK&gatewayAdapt=glo2jpn
   https://ja.aliexpress.com/store/4997284/pages/all-items.html?sortType=bestmatch_sort&shop_sortType=bestmatch_sort
   ```

2. スクリプトを実行します:  
   ```bash
   py main.py
   ```

3. **NGワード** を入力してください（カンマ区切り）。商品名にNGワードを含むアイテムはスクレイプ対象外になります。  

4. **「開始」** ボタンをクリックしてください。  

5. Chromeブラウザが開いたら、通貨を **JPY** に変更してください。（日本向けに設計されています）  

6. 「処理が完了しました」というメッセージが表示されるまで待ち、**「終了」** をクリックしてください。  

7. 結果は `登録.csv` に保存されます。  
   - 画像は `result` フォルダに保存されます。  

---

## ⚠️ Disclaimer / 免責事項

**EN:**  
Please use this scraper responsibly and respect AliExpress’s **terms of service**.  

**JP（日本語）:**  
本スクレイパーの使用は自己責任で行い、AliExpress の **利用規約** を尊重してください。  

---

## 👤 Author / 作者

[Ekans122](https://t.me/hiroyama_92)

---

## 📜 License / ライセンス

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  
このプロジェクトは **MITライセンス** の下で公開されています – 詳細は [LICENSE](LICENSE) を参照してください。  
