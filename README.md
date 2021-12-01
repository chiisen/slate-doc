# 介紹
slate 是類似 swagger 的 API 文件工具

# 注意事項
😣 Windows 有無法開啟的 bug
![無法開啟的 bug](https://i.imgur.com/KWVM3UK.png)
* Windows 請使用 WSL2 來執行下面操作

# 安裝
```
// 安裝 ruby
sudo apt-get install ruby 
// 安裝 ruby-dev
sudo apt-get install ruby-dev
// 安裝 bundler
sudo gem install bundler
```

# 編譯專案
專案下執行(類似 npm install)
```
bundle install
```

# 啟動專案
```
bundle exec middleman server
```
* 離開可按 Ctrl + C 關閉服務

# 瀏覽文件
```
http://localhost:4567
```
或
```
http://127.0.0.1:4567
```
# 文件架構
source > index.html.md 是主文件
可以用 markdown 語法撰寫文件
`# 標題` 會出現在左邊的大綱上，點擊可以超連結
![文件介面](https://i.imgur.com/FpezfQC.png)