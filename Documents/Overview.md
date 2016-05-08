# Overview
## Scrum Introduction
  1. Role
  2. Activities
  3. Artifects
    1. working software
    2. product backlog item

## 如何盡早發現 working software 的錯誤？
  1. Unit Test --> TDD
  1. V Model
    2. Unit Test, Integration Test, System Test, Acceptance Test

## 如何驗收 User Story
### 透過 Review 會議
  
### How to Demo

* 文件的缺點
    * 不易確認是否與系統相符
    * 誤解語意

以下是老婆對老公說的話：        

    我今天六點下班。
    如果你來了我還沒下班，你給我等著。
    如果我下班了你還沒來，你給我等著。


**Working software over comprehensive documentation** => Make a ==working document==.


## BDD with cucumber
### 3 Core Principles
資料來源：[BDDWiki](http://behaviourdriven.org)

1. Business and Technology should refer to the same system in the same way.
2. Any system should have an identified, verifiable value to the business.
3. Up-front analysis, design and planning all have a diminishing return.

### Cucumber
* 語法：Gherkin
* 可以支援的程式語言：==**Ruby**==、Java、.Net

### Calabash
* Open Source
* Written by Ruby
* Support Android Testing and iOS App Testing

[Sample Android Studio project](https://github.com/xamarin/test-cloud-samples/raw/master/Quickstarts/downloads/CreditCardValidator.AndroidStudio.zip)

[Calabash Quick Start for Android Studio](https://developer.xamarin.com/guides/testcloud/calabash/quickstarts/android-studio/)


## 自動化測試工具類型介紹
  1. 按照產生的方式
    coding <--> recording/playing
  2. 按照 App 的類型
    component based <--> Pattern recognition 圖形辨識

## Android 官方的測試工具
  1. uiautomator
  2. espresso


## References
[Getting Started with BDD](https://blog.hiptest.net/2016/04/28/getting-started-with-bdd-part-1/)

[搞笑談軟工](http://teddy-chen-tw.blogspot.in/2013/07/bdd1.html)

[BDDWiki](http://behaviourdriven.org)

[Specification by Example 中文版：團隊如何交付正確的軟體](https://en.wikipedia.org/wiki/Specification_by_example)

[Xamarin test cloud](calabashapi.xamarin.com)