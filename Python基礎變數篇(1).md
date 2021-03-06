# 變數是什麼？

一個變數的組成分為兩個，**變數名稱** 跟 **變數值**

變數是整個程式當中最重要的基本觀念，簡單來說就是一個會不斷變動的數值，主要用於儲存各種資料型態，而若要使用變數必須要先進行**宣告**

&nbsp;

#### 宣告
可以想成是做個初始設定，告知電腦你要使用這個變數，如果一個變數還沒宣告時就想用，電腦會不知道他的值是多少，進而發生錯誤，這部分會在後面的除錯篇做更詳盡的說明

&nbsp;

## 打個比方

現實中有一個箱子，箱子上面有貼一張標籤，且裡面可以放任何東西

例如:

可以在貼著box1標籤的箱子內放入蘋果

也可以在貼著box2標籤的箱子內放入香蕉

那其實變數就跟現實中的箱子一樣，有自己的標籤(變數名稱)，且可以放入任何東西(變數值)

![Alt Text](https://media.giphy.com/media/AANHiSJLrF8ga3WdXl/giphy.gif)
&nbsp;

## 接下來我們來看實際的變數是如何

```py
box1 = "apple"
box2 = "banana"
print(box1)
print(box2)
```

這邊我們宣告了box1, box2兩個變數，告訴電腦等下我們需要用到box1跟box2

而這邊的=可不是數學意思上的等於，我們在程式裡習慣稱為**設定** 或者指定(assign)，所以第一行可以說是把**box1這個變數設定為apple**(至於為什麼需要在apple兩側加上“，下一章的資料型態會再詳細解釋)

box1就是第一個變數的變數名稱，而apple就是box1的變數值

box2就是第二個變數的變數名稱，而banana就是box2的變數值

我們再利用```print()```列印出結果

```print()``` 是一個專門用來印出東西的語法，將想印出的東西放入括號內就能使用，因此我這邊將變數放入括號內，就能印出變數的值在**主控台**(console)上
&nbsp;

執行結果會長這樣

```
apple
banana
```
&nbsp;

## 練習

Q1: 請回答變數由哪兩個部分組成？

Q2: 請回答變數在使用前需先做什麼事？

Q3: 請回答以下輸出結果為何？
```py
a = 5
print(a)
```

Q4: 請根據上面那段程式碼回答以下問題
- 宣告是第幾行
- a變數的名稱跟值分別為何？

#### 下篇預告：Python基礎變數篇(2)-變數內可以放入哪些資料型態？
