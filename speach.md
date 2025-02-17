# 1

大家好，我今天要分享的主題是learning learning，

雖然資訊量可能有點龐大，但是我會盡可能的用比較通俗的語言來解釋，

而且我今天的重點是機器學習背後的哲學思考，

機器學習本身我只會進行概念性的介紹，

所以請各位同學不要對這個題目：又是機器學習又是哲學的感到害怕。

# 2

一個哲學思考首先來自一個問題，

所以這是本次分享的第一個問題：

為什麼要學習機器學習？

# 3

因為潮流嗎？機器學習是目前很夯的科技，好像不學就跟不上時代了，

是這樣嗎？

# 4

還是很多人或是媒體說機器人末日近在直尺。

為了避免人類被機器人統治或是毀滅的未來，我要來抱持著拯救人類的重大使命來學習機器學習。

或是：哎呀！反正這一定會發生，我倒好奇機器人到底是如何學習，最後把我們毀滅的？

# 5

或是有人想打造屬於自己的機器人好朋友，

甚至作為自己的人生伴侶？

# 6

還是覺得這是未來的關鍵，為了創造沒有貧窮、痛苦、疾病、戰爭的美好未來，我必須要學習機器學習？

# 7

還是想了解某個中央集權政府，如何透過機器學習對他的人民進行信用評價，評價太低的人工作機會受限、限制出境、限制生育在內的各種權利，已達到社會和諧？



我可以像暢銷書一樣，列出一堆原因，來說服你為什麼要學習機器學習，

不過這是個人主義當道的時代，別人的事似乎不足以構成自己利益而驅使學習動力。

# 8

那好，那至少為了你自己吧？你真的知道自己是怎麼進行學習的嗎？

你究竟如何透過學習變成你現在這個樣子？

包含你喜歡的課餘活動、包含你討厭的東西或是你厭惡的事情，

你的身上必然有著一套學習機制，然後透過與環境互動、成長，

最後成為現在的你，所以我們要問，這套機制究竟是如何運作的？

現在的我們究竟是如何被塑造而成的？

# 9

好啦，既然提到機器學習，就一定要提到這三個熱門關鍵字，

已經知道的人就當作複習，因為我還是要解釋給不知道的人了解一下。



這三個東西了，用一句話總結，那就是...

# 10

創造一個輸入與輸出的映射邏輯

# 11

我知道你們反應應該就是這樣，

我承認，這段話文謅謅的，有講跟沒講一樣，

所以請聽我慢慢解釋

# 12

首先，我們來想像一個塔，和一個小兵，

然後你是那個塔，那因為你不能移動，

所以你要關注的事情很簡單，只有一件事：

# 13

如果我和小兵的距離小於 50 ，我就要揍他，

看得懂程式碼的人可以看上面那個，這兩個是一樣的東西

# 14

如果我們把這個邏輯話成圖的話，可以這樣表示。

橫軸是距離空間，縱軸是揍人空間，

而這邊有一條線，可以把距離空間映射到揍人空間，

你看這裡，如果距離小於50，那根據曲線所對應的動作就是揍他，

而這裡，距離太遠，大於50，那根據曲線所對應的動作就是待機。

# 15

而剛剛那張圖，寫成數學式，可以寫成這樣

# 16

然後我剛剛的簡報，很巧妙的把這團資訊從自然語言空間，

# 17

映射到數學空間了。

也就是我剛剛在你的大腦裡面建立了一段文字和數學公式的映射關係，

當我顯示這個公式的時候，你會回想起我剛剛講的那段文字描述。

# 18

好，我相信映射的概念各位都有了，讓我們回到這三個熱門關鍵字，

# 19

這張圖左邊是人工智慧，中間是機器學習，右邊是深度學習。

常見的解釋是這樣的，

深度學習是機器學習中的一個分支，

而機器學習又是人工智慧中的一個特例。

不過其實他們之間的界線很模糊，這套解釋只是用來概念性的理解，

不是絕對的。

我們先來看一些人工智慧的例子。

# 20

決策樹，其實就是一堆條件判斷式構成，

經常被用來當遊戲 NPC 的簡易智能，

而最典型的例子就是文字冒險遊戲，當你觸發了某個條件，

劇情就會往那個方向去發展。

# 21

貪婪法，他會選擇當下最好或是最多回報的選擇，

比如這裡，12跟28選一個，明顯28比較大，所以選28，

而這裡，7跟9要選哪一個？選9，

當然這張圖也展現了貪婪法的缺點，

你有可能錯失了在其他你所拋棄的選項隱藏的巨大回報。

但是，如果一個最佳化問題有解，

你用貪婪法去解得到的解，很高的機率會是最佳解，

或許這解釋了為什麼人類這麼忠實於欲望，

畢竟當下選擇那個讓你回報最多、最開心的選擇，

很高的機率就是最佳解啊～

# 22

勢力圖，這個常用在即時戰略遊戲，

比如紅色有你的單位和建築物，藍色則是敵人單位和建築物，

你一定不會讓你單薄的部隊跑去敵人的勢力範圍裡面對吧？

# 23

A star 路徑搜尋演算法，常被用於遊戲角色的路徑規劃。

# 24

微波爐，他知道幾秒鐘該停止，這比起石頭已經很智慧了，然後因為是人造產物，所以它是人工智慧。

# 25

圖片分類演算法，這個我們等等會回來談它。

# 26

接下來是我最愛講的，線性回歸。

對沒錯，打開你的電腦試算表，畫個曲線圖，從資料找出那條線，你已經在使用人工智慧了。

# 27

好，所以一個人工智慧到底到什麼程度可以被叫做機器學習？

那我們來想想學習是怎麼回事？

# 28

回想你的過去，或是最近，特別是小時候，

是否犯過蠢，做了錯事，像這個月月一樣。

接著會發生什麼事情？

# 29

你會被各種糾正。

然後你就學到不能這樣做，

所以學習的一大前提是，你要先去嘗試錯誤的方法。

# 30

在增強式學習，有一個專有名詞叫做獎勵。

# 31

他的含意其實就是我們常說的：糖與鞭子，

英文的諺語是棒子和胡蘿蔔，

就是獎勵與懲罰。

透過這套機制，把學習對象的邏輯引導至我們期望的映射關係。

# 32

對人而言學習有成本，對機器而言學習同樣也有成本，

特別是時間，學習的過程需要透過不斷的嘗試錯誤，所以是十分耗費時間的。

這也是為什麼在我們社會中，人才是可貴的，

而且也是為什麼，社會想要積極發展機器學習來解決人才短缺的問題。

因為人會死，但是機器學習的產物可以存檔繼續使用。

# 33

接著我們來看看機器學習的過程大概是怎樣，我以線性回歸舉例。

# 34

我們都知道一個截距和斜率可以確立一條直線，

假設我們現在有一條線，我們如何評價這條線和資料的吻合程度呢？

透過這種方式我們度量資料與假設直線的距離，

然後把這些距離的絕對值相加，我們就知道資料與這條直線的吻合程度了，

其值越大，代表差異越大，越不吻合。

所以電腦可能會嘗試把這條線往左移、往右移、順時針旋轉、逆時針旋轉，

最後找出誤差值最小的beta 0 和 beta 1

# 35

我要先聲明，在這種簡單線性回歸，已經有公式解了，試算表跑簡單線性回歸不會像我剛剛這樣講的嘗試錯誤，而是直接套公式求解，

我只是要演示，機器學習嘗試錯誤的過程。

# 36

好，我們現在知道什麼是人工智慧，什麼是機器學習了，

那深度學習又什麼玩意兒？

# 37

深度學習就是由一種叫做類神經網路的演算法所實現的機器學習，

而這就是類神經網路內所謂的神經元，

其實就是輸入乘上權值，再經過激勵函數映射後輸出。

# 38

可以看到他這種演算法其實是受到生物的神經元細胞所啟發，

神經元從這邊接受電氣訊號，然後從這邊放電去刺激其他神經元。

# 39

關於深度學習這個名詞背後有一段小故事

# 40

這是單層的類神經網路，

而這是多層的類神經網路，

深度學習通常是指大於三層的類神經網路。

# 41

類神經網路其實很早就發展出來了，

但是當層數太多，會面臨難以訓練的問題，

這個問題要用數學來解釋，我這邊就不多做描述，各位只要知道他們朋到瓶頸就好，

於是當時的類神經網路熱潮過後，學術界就對類神經網路這個名詞感到噁心，

而這個hinton教授在類神經網路領域的堅持不懈，

最後終於發展出解決多層網路訓練困難的問題，

於是他就發明了深度學習這個名詞，

然後還嘲諷小於3層的類神經網路都是淺層網路。

# 43

這位就是hinton教授。

# 44

我們來看看這個神經元，

他其實就是數學公式，

透過把這些輸入值乘上對應的權重，

再透過激勵函數激發。

不過這樣看起來似乎有點冷冰冰的，

一部分的人可能也聽不懂我在說什麼。

# 45

那我舉個例子，

這裡有三個影響你會不會跑去吃飯的因子，

誘惑因子是周遭有人在吃東西，誘惑你去吃飯，

飢餓因子是你肚子飢餓的程度，

而財富因子是你身上持有的現金，

這些都會影響你現在想不想去買東西吃，

應該很直觀吧？

這些因子對吃飯函數的映射關係受到這三個權值影響，

至於這些權值是多少呢？我不知道，

# 36

接著我可以採樣，

紀錄你當前的誘惑、飢餓、財富狀態，以及你有沒有跑去吃飯，

做出類似這樣的統計資料。

然後就像剛剛線性回歸一樣，我把這些資料丟進去上面這個公式，

然後嘗試各種不同的權值，

理論上我會找出一組權值，帶入這些資料的因子後，得到吃飯函數就跟我紀錄你吃飯的行為很接近。

哀，可是問題來了，他這個激勵函數輸出的值是連續的，

# 49

跟剛剛這個用判斷式產生的映射關係不一樣，

介於吃飯跟不吃飯中間的數值我要怎麼處理？

# 50

增強式學習有一個東西叫做策略，

他把你的決策用機率來表示

# 51

所以這個介於0到1的輸出結果，就是你決策要不要去吃飯的機率，

如果今天輸出值是0.5，代表你有可能去吃飯也有可能不去吃飯，這機率一半一半。

# 52

然後我們用這個觀念回來看貪婪法，

他就是讓你的決策策略，選擇最好的那個選項的機率是100%。

# 53

好，經過剛剛那些資料，我訓練出來的結果就是我得到了三個數字，

w1 w2 w3，可是這三組數字跟你會不會吃飯之間有並沒有演繹關係，

我不能解釋未什麼w1是這個數字，w2是這個數字，而w3是那個數字。

# 54

這就像是你去問匠人，這個力道或是時間要怎麼拿捏，

他可能也只能告訴你憑著經驗或是直覺，

類神經網路的學習結果也像是經驗，

有效，但是難以言喻。

# 55

這個是google的圖片分類演算法十分有名的失誤，

他把這兩位朋友的照片分類成黑猩猩，

接下來我會介紹這怎麼發生的。

# 56

還記得我先前提到的誤差嗎？

這張圖顯示的是，隨著持續進行訓練，

你的映射邏輯會越來越匹配訓練資料，

但是這個映射邏輯對真實環境的誤差卻會越來越大。

# 57

什麼是訓練資料呢？就是像是我剛剛採樣的這些資料，

那什麼是測試資料呢？就是我再另外採樣一組資料，

但是這組資料在訓練過程並不會使用到。

# 58

這個現象叫做過度擬合，

左邊這個是完全沒有擬合訓練資料，

中間是適度的擬合訓練資料，

右邊這就是過度擬合訓練資料，

換句話說就是我們訓練出來的人工智慧，

過於仰賴訓練時的資料，

換句話說，它過度依賴經驗。

所以看到google的分類失誤，我們不能嘲笑他，

即便是人類，如果一個10歲的小孩從來沒看過黑人，

但是他看過黑猩猩，

今天你突然拿著黑人的照片給他看，

他可能也會辨別成猩猩。

我想事件發生後， google的資料科學家應該立馬找了一堆黑人的照片丟進去訓練，告訴演算法這是人，不是猩猩。

# 59

接著我們回顧一下，

人工智慧的邏輯是一種空間與空間之間的映射關係，

而人類的反應其實也是一種非線性映射邏輯；

# 60

機器與人類的學習都需要成本，特別是時間；

# 61

機器與人類的學習過程都有糖與鞭子；

# 62

人工智慧的策略可以像是人類一般，做出機率性的決策；

# 63

深度學習的成果就像人類學習獲得的經驗一樣，是透過歸納而非演繹產生的，因此它可以有效但是難以言喻；

# 64

貪婪，雖然問題不見得有解，但是如果有解的話，貪婪法求得的解通常是最佳解；

# 65

人和機器學習都會被經驗所誤導。



# 66

機器學習就像一面鏡子，我們看著機器如何學習，但是機器學習所顯示的，其實是我們人類自身如何學習。

# 67

我的分享到此結束，感謝各位聆聽。