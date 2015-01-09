這是一個很長很長的故事
===============

<a href="http://event.kkbox.com/user/stories/168216244" target="_blank">![](https://github.com/KKBOX-design-sharing/intro/blob/master/emotion_4.jpg)</a> 





我是大標
===============


### 我是中標題
## 我是中標題
# 我是中標題

常和朋友談到日本歌壇已經很久沒有誕生歌姬級的人物了，或許是好聲音還沒被挖掘，又或許是好歌手還沒遇上對的歌，但有個名字值得樂迷們先牢牢記住：「塩之谷早耶香」。
出生於1994年的塩之谷早耶香，踏入歌壇的契機是2011年由LDH公司主辦的「EXILE Presents VOCAL BATTLE AUDITION 3～For Girls～」，塩之谷早耶香在約3萬名報名者中一舉晉級主唱部門最終決選，雖然最後未能獲得優勝，但在社長HIRO慧眼賞識下，她開始於EXILE PROFESSIONAL GYM福岡校接受培訓。接著塩之谷早耶香參加2012年「KING RECORDS Presents Dream Vocal Audition」，從約1萬名報名者中脫穎而出，奪下「Dream Vocalist loved by ViVi」優勝，也終於獲得發行唱片出道的機會。

出道第一年密集地推出4張單曲，第2張單曲【單戀/Smile again】中的《單戀》，邀請打造出EXILE放浪兄弟《Lovers Again》、《Ti Amo我愛你》等多首暢銷歌曲的製作人「Jin Nakamura」作曲，延續出道單曲風格，唱出戀情無法圓滿的哀愁情感。2014年推出的第5張單曲《Like a flower》則跳脫以往氣質抒情路線，造型色彩繽紛、歌曲節奏輕快，唱出等身大的自由活潑，這也是她在日本公信榜上表現最為亮眼的單曲。至今推出5張單曲，都分別tie-up了電影、日劇、大型活動等，作足宣傳，唱片公司對她的大力栽培與期許也可見一斑。


台灣觀眾相當耳熟能詳的「關８比賽中」卡拉OK比賽單元，塩之谷早耶香也曾數次參賽，嬌小身材所展現出的驚人爆發力與廣闊音域、極具穿透力的歌聲，屢屢獲得高分。再次證明她歌唱底子堅強的同時，也逐漸為自己打開知名度。


```

// 自訂 mixin 斷點樣式
@mixin _break($screen: mobile)
	$map: map-get($break_layout, $screen)
	$break: map-get($map, "break")
	$layout: map-get($map, "layout")

	+susy-breakpoint($break, $layout)
		@content


.module
	height: 300px
	+_break(mobile)
		+container()
	
	+_break(pad)
		+container()
	
	+_break(desktop)
		+container()

.o1
	+_break(desktop)
		+container()
		+span(2)
		height: 100px
		background: #689
		padding: 20px

```
