禪與 App 維修的藝術
-------------------

幾年前我讀了一本叫做《禪與摩托車維修的藝術》的書。這本不算薄書大概的內
容是這樣：作者不斷思考當代人的處境，發現當代人處在一種前所未有的無力感
中，而這種無力感的來源是科技。

科技的發展一方面讓人享受便利，但另一方面卻讓人更無力，現代人離不開科技，
但科技並不透命，科技的複雜卻讓人難以完全理解科技，人們無法完全理解每天
都在使用的事物背後是怎麼運作的。當某項科技出了差錯，某台機器故障，人們
不知道應該從何下手，因為科技，人們失去了掌握自己生活中種種的權力。

後來作者又講到，從西方傳統的科學哲學，也無法解決這種處境。科學精神就在
於觀測與證明，而現在有太多的現象無法觀測，也無法給予直接的證明—我們和
絕大多數的台灣人一樣缺乏西方科學哲學訓練，姑且跳過這段討論。總之，作者
認為在二十世紀應該要有一門新的哲學，這門哲學的精神是鼓勵人們觀察事物的
背後，了解科技背後如何運作，人們有能力對自己的生活重新掌權，而如果無法
直接觀測，那麼，我們就該重新強調西方科學傳統被排拒的直覺與想像力。

用戶使用我們的 App，還有我們在修 bug 的時候，往往也陷入這種無力感：用
戶可能天天都在用我們的 App，但也搞不清楚我們是怎麼把 App 寫出來的，App
有問題不知道怎麼辦。我們在修 bug 的時候，也經常搞不清楚用戶是在怎樣的
環境下執行，客訴如雪片般飛來我們卻無法重現問題，我們也沒辦法看到蘋果的
程式碼，不見得知道蘋果的 library 到底做了什麼，當問題發生的時候，我們
和用戶一樣束手無策。

那我們能做什麼呢？我們的眼光應該要從那些眩目的事物上稍微移開，我們或許
會知道很多第三方 library，知道很多 cocoapods 可以用，我們可以用很快的
速度拼裝出一個 App，但我們要了解被系統 library 隔絕開來的底下是怎麼運
作，像 Objective-C run time 是怎麼回事，才有辦法理解問題，同時細心觀察
我們手上有哪些線索，像 crash report，進而發揮想像力，想像問題出現的時
候，到底發生了什麼。

接下來我們會進入幾個實戰案例。
