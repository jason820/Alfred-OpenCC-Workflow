# 介紹

一個Alfred Workflow，便於透過[OpenCC](https://github.com/BYVoid/OpenCC)進行簡繁轉換。

# 安裝

##  1. OpenCC
Homebrew可以幫你很簡單的安裝好OpenCC，在終端機輸入：

	brew install opencc
	
當然也可以自己下載原始碼編譯：

	git https://github.com/BYVoid/OpenCC.git
	cd OpenCC
	make
	sudo make install

安裝完成，在終端機可以查詢安裝的版本。

	opencc --version

##  2. Alfred Workflow

把Open CC.alfredworkflow下載回去，然後直接拖曳到Alfred的Workflow畫面就可以把它加入Alfred。

# 使用

1. 先把要轉換的文字command+c拷貝到剪貼簿。
2. 快捷鍵叫出Alfred視窗。
3. 輸入tw2s或是s2tw進行簡繁轉換。
4. 轉換完成的結果還是放在剪貼簿裡，這按command+v貼到需要的位置即可。


