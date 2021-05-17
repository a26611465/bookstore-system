# bookstore-system

（一）期中專案簡介：
	本專案程式為一個線上書城交易系統，使用者可以在系統上購書，而系統管理員可以從後台更改書籍資料及營運報表

（二）角色功能介紹：
	顧客：查詢書籍庫存、價格、與購買等功能
	管理員：修改書籍庫存、價格與查看營收報表等功能
（三）專案測試劇本
	在 inventory.txt 預存書籍
	Think python;520;300;10;2015/12/31
	Introduction to algorithms;4950;2000;20;2009/09/01
	Introduction to management science;1420;800;15;2019/04/01	

	1.執行程式
		系統顯示書籍庫存、價格等資訊

	2.選擇進入管理員模式或是直接購買書籍
		2.1管理員模式(action輸入AAA)
			可選擇使用五種功能模組(後台功能輸入：1~5任一模組)
			1. Show information about books
			2. Update the price of an item
					輸入修改項目:價格
			3. Update the stock of an item
					輸入修改項目:冊數
			4. Add new book to the store
					數入書本資訊 ex: Show information about books;1380;900;20;2020/05/27
			5. Go back to the initial screen	
		2.2直接購買書籍(action輸入書籍代碼）
			如有庫存可以直接購買，交易成功

	3.回到初始介面
		系統顯示書籍庫存、價格等資訊
		（系統會自動更新inventory.txt 和 Finstat.txt ）
