# Ruby 學習資源

本文列出 Ruby 相關的學習資源，以供有心學習 Ruby 的同好們參考。

## Ruby 程式設計

- [https://www.ruby-lang.org/](https://www.ruby-lang.org/)：官方網站，有一些文件可看
- Ruby Doc：查 Ruby API 用
  [[連結](http://ruby-doc.org/)]
- Ruby User's Guide：快速學習 Ruby 的語法，原版是由 Ruby 之父松本行弘以日文撰寫
  [[英譯](http://www.rubyist.net/~slagell/ruby/)]
  [[中譯](http://guides.ruby.tw/ruby/)]
- Beginning Ruby, 3rd edition：簡明的 Ruby 入門書
  [[連結](http://www.apress.com/9781484212790)]
- Learn to Program：新手導向的入門書
  [[連結](https://pine.fm/LearnToProgram/)]
- Learn Ruby the Hard Way：含許多練習的入門書
  [[連結](http://learnrubythehardway.org/book/)]
  [[中譯](http://lrthw.github.io/)]
- The Well-Grounded Rubyist, 2nd edition：著重觀念的 Ruby 程式設計書籍
  [[連結](https://www.manning.com/books/the-well-grounded-rubyist-second-edition)]
- TutorialsPoint 的 Ruby 教程
  [[連結](http://www.tutorialspoint.com/ruby/)]
- Programming Ruby：具指標性的 Ruby 教材，Ruby 版本略舊
  [[連結](https://pragprog.com/book/ruby4/programming-ruby-1-9-2-0)]
  [[舊版](http://ruby-doc.com/docs/ProgrammingRuby/)]
- Ruby Under a Microscope：講解 Ruby 內部實作的書籍，非一般 Ruby 入門教材
  [[連結](http://patshaughnessy.net/ruby-under-a-microscope)]

## 開發方法論

- Practical Object-Oriented Design in Ruby: An Agile Primer：以 Ruby 為例，講解物件導向程式設計的書
  [[連結](http://www.poodr.com/)]
  [[中譯](http://www.drmaster.com.tw/Bookinfo.asp?BookID=MP11505)]
- Effective Ruby：一些 Ruby 的實務和經驗
  [[連結](https://www.effectiveruby.com/)]
  [[中譯](http://books.gotop.com.tw/v_ACL043600)]
- Test Driven Development in ruby: 以測試導向開發 (TDD, Test-Driven Development) 為主軸，講解 Ruby 程式設計。
  [[連結](http://www.apress.com/gp/book/9781484226377)]


## 線上學習網站

- Codecademy：免費線上練習程式設計的網站，可付費升級以取得部分獨特內容
  [[連結](https://www.codecademy.com/)]
- RubyMonk：免費線上互動式 Ruby 學習網站
  [[連結](https://rubymonk.com/)]
- Ruby Koans：下載學習 Ruby 程式設計
  [[連結](http://rubykoans.com/)]
- SoloLearn：免費線上互動式程式設計學習網站，有多種語言，包括 Ruby 在內
  [[連結](https://www.sololearn.com/)]
- Code School：線上練習程式設計的網站，包括 HTML, CSS, JavaScript, Ruby, Python 等課程，大部分課程需付費
  [[連結](https://www.codeschool.com/)]
- LauchSchool (原 Tealeaf)：紮實的線上課程，費用較高，有真人導師協助學習
  [[連結](https://launchschool.com/)]


## 解題網站

熟悉 Ruby 語法後，可以到下列網站練功。有些題目有相當難度，做不出來也不用太灰心。

- [LeetCode](https://leetcode.com/)：線上練習
- [HackerRank](https://www.hackerrank.com/)：線上練習
- [HackerEarth](https://www.hackerearth.com/)：線上練習
- [exercism](http://exercism.io/)：下載習題於本地端練習


## Web 開發

建議想學習 web 開發的初學者，先將 [HTTP 的基礎概念](http://www.tutorialspoint.com//http/index.htm) 看完一次，但不需強記那些協定的細節。然後，可以依照前端 (frontend) 和後端 (backend) 分頭學習，以 Ruby 社群來說，初學者可以先透過 Sinatra 來學習 web 開發，在學到 web form 和 ajax 時，就會用到後端，另外，資料庫也需要透過後端程式和前端連結。對於有經驗的開發者，則可直接學習 Ruby on Rails。

### 前端

- HTML：靜態的網頁內容
- CSS：靜態的網頁形式
- JavaScript：動態的網頁動作。對於初學者來說，先學基本的 JavaScript 語法和 [jQuery](https://jquery.com/)。以後再視需要學習前端框架。

### 後端

傳統上來說，後端是由 Perl、PHP、ASP、JSP 等語言負責，但後端不限於某種特定的語言。以 Ruby 社群來說，可由下列框架入門：

- [Ruby on Rails](http://rubyonrails.org/)：Ruby 社群最知名的 MVC 框架
- [Sinatra](http://www.sinatrarb.com/)：一個微框架 (micro-framework)，非 MVC 框架

或是這些新的框架

- [Hanami](http://hanamirb.org/)：現代化的 MVC 框架
- [Padrino](http://padrinorb.com/)：基於 Sinatra 的 MVC 框架

### 資料端

資料庫有相當多的實作品，以 web application 來說，可先從以下兩種資料庫擇一學習：

- MySQL/MariaDB
- PostgreSQL


## Ruby on Rails

Ruby 中最知名的 web framework。但 Rails 較適合已有一定 web application 開發經驗，想要快速開發新產品的開發者。

### Rails 5

- Rails Guide：官方文件，略為學過 Rails 後再看，比較容易上手
  [[連結](http://guides.rubyonrails.org/)]
- 為你自己學 Ruby on Rails：高見龍 (eddie) 先生所撰寫的 Rails 書籍
  [[線上](http://railsbook.tw/)][[紙本](http://books.gotop.com.tw/v_ACL050300)]
- Ruby on Rails Tutorial：國外最知名的 Rails 入門教程
  [[連結](https://www.railstutorial.org/)]
- Agile Web Development with Rails 5：DHH 參與編寫的 Rails 教程
  [[連結](https://pragprog.com/book/rails5/agile-web-development-with-rails-5)]
- Learning Rails 5
  [[連結](http://shop.oreilly.com/product/0636920039822.do)]

### Rails 4

- Rails, Angular, Postgres, and Bootstrap：綜合性書籍，建議有一些網頁程式的經驗再看
  [[連結](https://pragprog.com/book/dcbang/rails-angular-postgres-and-bootstrap)]
- RailsBridge Docs：簡易的 Rails 教程，可以按部就班學習。
  [[連結](http://railsbridge-docs-zh-tw.herokuapp.com/docs/)]
- Rails Girls 指南：可跟著練習的教程。
  [[連結](http://railsgirls.tw/)]
- Ruby on Rails 實戰聖經：國內有名的 Rails 參考書。
  [[連結](https://ihower.tw/rails4/)]
- Rails 101：目前改為免費線上課程。
  [[連結](http://courses.growthschool.com/courses/rails-101)]
- Rails 102：一些較進階的 Rails 相關知識。
  [[連結](https://www.gitbook.com/book/rocodev/rails-102/details)]
- The Rails Way：將 Rails 詳細講一次的大部頭書籍，適合學過一陣子 Rails 後再看。
  [[連結](http://amzn.to/1Q1PtL4)]


## Sinatra

一個 micro-framework，可用來快速建立網頁應用程式。對於不熟悉 web 開發的程式設計師而言，先學 Sinatra 比較容易上手。但 Sinatra 較不適合用來建立大型網站。

- Sinatra 官網，有一些文件可看。
  [[連結](http://www.sinatrarb.com/)]
- Sinatra Up and Running：第一本 Sinatra 的實體書籍。
  [[連結](http://shop.oreilly.com/product/0636920019664.do)]
- Jump Start Sinatra：電子和實體書籍。
  [[連結](http://www.sitepoint.com/store/jump-start-sinatra/)]


## Git

最流行的分散式版本管理系統，Linux 之父 Linus Torvalds 的作品。

- 為你自己學 Git：高見龍 (eddie) 先生所撰寫的 Git 書籍
  [[線上](http://gitbook.tw/)]
- Pro Git：免費電子書，也有實體書籍。
  [[連結](https://git-scm.com/book/en/v2)]

建議到 [GitHub](https://github.com/) 註冊帳號，以存放程式碼，帳號本身為免費，如果需要私有 repo 時可付費。也可到 [Bitbucket](https://bitbucket.org/) 註冊帳號，存放私有 repo 不需收費。


## 適用 Rails、Sinatra 和其他 Ruby 網站的 hosting 方案

PaaS 的好處是不需管理站台，但收費會略高

- [Heroku](https://www.heroku.com/)：提供免費額度可供練習
- [Engine Yard](https://www.engineyard.com/)
- [Google Cloud Platform](https://cloud.google.com/)
- [OpenShift](https://www.openshift.com/)：有免費額度可供練習

*註：OpenShift 上 Ruby 及其他相關套件的版本較舊，可能會在部署時發生問題，請小心服用。*

VPS 的好處是收費相對較低，但需自行管理站台

- [Linode](https://www.linode.com/)
- [DigitalOcean](https://www.digitalocean.com/)
- [Vultr](https://www.vultr.com/)


## Mobile apps

透過 [RubyMotion](http://www.rubymotion.com/) 可將 Ruby 程式碼轉為原生的 iOS、Mac OS 及 Android 平台的應用程式。這是一套商業軟體，基本功能免費，進階功能需付費，請需要的朋友自行參考。


## 綜合性應用

- Ruby Cookbook: 綜合性 Ruby 技巧及應用。
  [[連結](http://shop.oreilly.com/product/9780596523695.do)]
- The Ruby Way: 綜合性 Ruby 技巧及應用。
  [[連結](http://therubyway.io/)]
- [The Ruby Toolbox](https://www.ruby-toolbox.com/)：
  列出各種情境可用的 gems，有一些指標像是開發活躍度、下載次數等可參考
- [Awesome Ruby](http://awesome-ruby.com/)：
  列出許多 Ruby 函式庫和框架，可供開發者參考
- [Awesome Ruby (from LibHunt)](https://ruby.libhunt.com/)；另一個整理過的 Awesome Ruby 站台
- Text Processing with Ruby：利用 Ruby 進行文字處理相關任務。
  [[連結](https://pragprog.com/book/rmtpruby/text-processing-with-ruby)]
- Ruby Performance Optimization：各種加速 Ruby 專案的技巧。
  [[連結](https://pragprog.com/book/adrpo/ruby-performance-optimization)]
- Build Awesome Command-Line Applications in Ruby 2：用 Ruby 撰寫終端機程式
  [[連結](https://pragprog.com/book/dccar2/build-awesome-command-line-applications-in-ruby-2)]
- [Ruby Quicktips](http://rubyquicktips.com/)：一些簡短而實用的 Ruby 程式碼


## 遊戲

什麼？Ruby 可以用來做遊戲？用 [Gosu](https://www.libgosu.org/) 就可以做出一個 2D 遊戲了。

- Learn Game Programming with Ruby：實體和電子書籍
  [[連結](https://pragprog.com/book/msgpkids/learn-game-programming-with-ruby)]
- Developing Games with Ruby：電子書，可免費線上觀看及付費下載
  [[連結](https://leanpub.com/developing-games-with-ruby/)]

以下是另一本有趣的 Ruby 書：

- Mazes for Programmers：用 Ruby 製作迷宮
  [[連結](https://pragprog.com/book/jbmaze/mazes-for-programmers)]


## 電子報

- [Ruby Weekly](http://rubyweekly.com/)
- [Green Ruby](http://greenruby.org/)
- [Ruby Asia](http://rubyasia.com/)

## 個人網站

一些 Ruby/Rails 前輩的網站，按網路代名的字母排序。

- [eddie](http://blog.eddie.com.tw/)
- [ihower](https://ihower.tw/)
- [ryudo](http://ryudo.tw/)
- [xdite](http://xdite.net/)

## 社群

- [Rails Taiwan](http://www.meetup.com/rails-taiwan/)：台北和高雄的 Meetup
- [RailsFun](http://railsfun.tw/)：Rails 社群，包括線上討論區和實體聚會
- [Ruby Taiwan](https://www.facebook.com/groups/142197385837507/)：Facebook 社團
- [Ruby on Rails 讀書會](https://www.facebook.com/groups/208890269174940/)：Facebook 社團
- [Ruby on Rails 新手村](https://www.facebook.com/groups/670532946312104/)：Facebook 社團

## 研討會

以東亞的研討會為主。

- [RubyConf Taiwan](http://rubyconf.tw/)：台灣的 Ruby 研討會
- [RubyConf China](http://www.rubyconfchina.org/)：中國大陸的 Ruby 研討會
- [Ruby Kaigi](http://rubykaigi.org/)：日本的 Ruby 研討會
- [Rails Pacific](http://www.railspacific.com/)：亞洲區的 Rails 研討會

如果有機會出國，可以參考 [Ruby Conferences](http://rubyconferences.org/) 網站，有全世界的 Ruby 相關研究會短訊。

## 商業課程

小弟和下列團體沒對價關係，各位網友可放心。
有些網友比較喜歡上課，故放在此處，請各位自行參考。

- [五倍紅寶石](https://5xruby.tw/)：提供 Ruby、Rails、iOS 等課程
- [ALPHAcamp](https://www.alphacamp.co/)：提供 Rails、iOS 和行銷等課程，以創業為目標，需面試
- [GrowthSchool](http://www.growthschool.com/)：提供 Rails、敏捷開發、Growth Hack 等課程
- [飛鳥學院](http://asukademy.com/)：提供網頁前端、PHP、Rails、iOS 等課程
