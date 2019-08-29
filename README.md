# 2nd-ML100Days

### Please paste the URL from Github to https://nbviewer.jupyter.org/ if failed to load.

Day001 資料介紹與評估資料：挑戰是什麼?動手分析前請三思

Day002 EDA-1/讀取資料EDA: Data summary：如何讀取資料以及萃取出想要了解的信息

Day003 3-1如何新建一個 dataframe?3-2 如何讀取其他資料? (非 csv 的資料，如圖檔、純文字檔、json 等)

Day004 EDA: 欄位的資料類型介紹及處理：了解資料在 pandas 中可以表示的類型

Day005 EDA資料分佈：用統計方式描述資料

Day006 EDA: Outlier 及處理：偵測與處理例外數值點：1. 透過常用的偵測方法找到例外 2. 判斷例外是否正常

Day007 常用的數值取代：中位數與分位數連續數值標準化：偵測與處理例外數值 1. 缺值或例外取代 2. 數據標準化

Day008 DataFrame operationData frame merge/常用的 DataFrame 操作：1. 常見的資料操作方法 2. 資料表串接

Day009 EDA:correlation/相關係數簡介：1.了解相關係數 2.利用相關係數直觀地理解對欄位與預測目標之間的關係

Day010 EDA from Correlation：深入了解資料，從 correlation 的結果下手

Day011 EDA: 不同數值範圍間的特徵如何檢視/繪圖與樣式Kernel Density Estimation(KDE)

Day012 EDA: 把連續型變數離散化：簡化連續性變數

Day013 程式實作 把連續型變數離散化：深入了解資料，從簡化後的離散變數下手

Day014 Subplots：探索性資料分析-資料視覺化-多圖檢視1.將數據分組一次呈現2.把同一組資料相關的數據一次攤在面前

Day015 探索性資料分析-資料視覺化-熱像圖：以直觀的方式檢視變數間的相關性/格狀圖：繪製變數間的散佈圖及分布 

Day016 模型初體驗Logistic Regression：使用任何複雜的模型之前，有一個最簡單的模型當作 baseline 是一個好習慣

Day017 特徵工程簡介：介紹機器學習完整步驟中，特徵工程的位置以及流程架構

Day018 特徵類型：特徵工程依照特徵類型，做法不同，大致可分為數值/類別/時間型三類特徵

Day019 數值型特徵-補缺失值與標準化：數值型特徵首先必須填補缺值與標準化，在此複習並展示對預測結果的差異

Day020 數值型特徵 - 去除離群值：數值型特徵若出現少量的離群值，則需要去除以保持其餘數據不被影響

Day021 數值型特徵 - 去除偏態：數值型特徵若分布明顯偏一邊，則需去除偏態以消除預測的偏差

Day022 類別型特徵 - 基礎處理：介紹類別型特徵最基礎的作法 : 標籤編碼與獨熱編碼

Day023 類別型特徵 - 均值編碼：類別型特徵最重要的編碼 : 均值編碼，將標籤以目標均值取代

Day024 類別型特徵 - 類別型特徵常見編碼 : 計數編碼對應出現頻率相關的特徵，雜湊編碼對應眾多類別而無法排序的特徵

Day025 時間型特徵：時間型特徵可抽取出多個子特徵，或周期化，或取出連續時段內的次數

Day026 特徵組合 - 數值與數值組合：特徵組合的基礎 : 以四則運算的各種方式，組合成更具預測力的特徵

Day027 特徵組合 - 類別與數值組合：類別型對數值型特徵可以做群聚編碼，與目標均值編碼類似，但用途不同

Day028 特徵選擇：介紹常見的幾種特徵篩選方式

Day029 特徵評估：介紹並比較兩種重要的特徵評估方式，協助檢測特徵的重要性

Day030 分類型特徵優化 - 葉編碼：葉編碼 : 適用於分類問題的樹狀預估模型改良

Day031 機器學習概論：機器學習、深度學習與人工智慧差別是甚麼? 機器學習又有甚麼主題應用?

Day032 機器學習-流程與步驟：資料前處理 -> 訓練/測試集切分 ->選定目標與評估基準 -> 建立模型 -> 調整參數

Day033 機器如何學習?了解機器學習的定義，過擬合 (Overfit) 是甚麼，該如何解決

Day034 訓練/測試集切分的概念：為何要做訓練/測試集切分？有什麼切分的方法？

Day035 regression vs. classification：回歸問題與分類問題的區別？如何定義專案的目標

Day036 評估指標選定/evaluation metrics：專案該如何選擇評估指標？常用指標有哪些？

Day037 regression model 介紹 - 線性迴歸/羅吉斯回歸：線性迴歸/羅吉斯回歸模型的理論基礎與使用時的注意事項

Day038 regression model 程式碼撰寫：如何使用 Scikit-learn 撰寫線性迴歸/羅吉斯回歸模型的程式碼

Day039 regression model 介紹 - LASSO 回歸/ Ridge 回歸：LASSO 回歸/ Ridge 回歸的理論基礎與與使用時的注意事項

Day040 regression model 程式碼撰寫：使用 Scikit-learn 撰寫 LASSO 回歸/ Ridge 回歸模型的程式碼

Day041 tree based model - 決策樹 (Decision Tree) 模型介紹：決策樹 (Decision Tree) 模型的理論基礎與使用時的注意事項

Day042 tree based model - 決策樹程式碼撰寫：使用 Scikit-learn 撰寫決策樹 (Decision Tree) 模型的程式碼

Day043 tree based model - 隨機森林 (Random Forest) 介紹：理論基礎與使用時的注意事項

Day044 tree based model - 隨機森林程式碼撰寫：使用 Scikit-learn 撰寫隨機森林 (Random Forest) 模型的程式碼

Day045 tree based model - 梯度提升機 (Gradient Boosting Machine) 介紹模型理論基礎與使用時的注意事項

Day046 tree based model - 梯度提升機程式碼撰寫：使用 Scikit-learn 撰寫

Day047 超參數調整與優化：什麼是超參數 (Hyper-paramter) ? 如何正確的調整超參數？常用的調參方法為何？

Day048 Kaggle 競賽平台介紹：介紹全球最大的資料科學競賽網站。如何參加競賽？

Day049 集成方法 : 混合泛化(Blending)：什麼是集成? 集成方法有哪些? Blending 的寫作方法與效果為何?

Day050 集成方法 : 堆疊泛化(Stacking)：Stacking 的設計方向與主要用途是什麼? 通常會使用什麼套件實作?

Day051 Kaggle 期中考：優惠券使用預測

Day052 Kaggle 期中考：優惠券使用預測

Day053 Kaggle 期中考：優惠券使用預測

Day054 Clustering 1 非監督式機器學習簡介：非監督式學習簡介、應用場景

Day055 Clustering 2 聚類算法：K-means

Day056 K-mean 觀察 : 使用輪廓分析：非監督模型要以特殊評估方法(而非評估函數)來衡量 : 輪廓分析

Day057 Clustering 3 階層分群算法：Hierarchical Clustering

Day058 階層分群法 觀察 : 使用 2D 樣版資料集：非監督評估方法 : 2D樣版資料集是什麼? 如何生成與使用?

Day059 Dimension Reduction 1 降維方法-主成份分析：PCA

Day060 PCA 觀察 : 使用手寫辨識資料集：以較複雜的範例 : sklearn版手寫辨識資料集, 展示PCA的降維與資料解釋能力

Day061 Dimension Reduction 2 降維方法-T-SNE

Day062 T-SNE 觀察 : 分群與流形還原：什麼是流形還原? 除了 T-SNE 之外還有那些常見的流形還原方法?

Day063 神經網路介紹：Neural Network 簡介

Day064 深度學習體驗 : 模型調整與學習曲線：介紹體驗平台 TensorFlow PlayGround，並初步了解模型的調整

Day065 深度學習體驗 : 啟動函數與正規化：在 TF PlayGround 上，體驗進階版的深度學習參數調整

Day066 Keras 安裝與介紹：如何安裝 Keras 套件

Day067 Keras Dataset：Keras embedded dataset的介紹與應用

Day068 Keras Sequential API：序列模型搭建網路

Day069 Keras Module API：Keras Module API的介紹與應用

Day070 Multi-layer Perception多層感知：MLP簡介

Day071 損失函數：損失函數的介紹與應用

Day072 啟動函數：啟動函數的介紹與應用

Day073 梯度下降Gradient Descent：梯度下降Gradient Descent簡介

Day074 Gradient Descent 數學原理：介紹梯度下降的基礎數學原理

Day075 BackPropagation：反向式傳播簡介

Day076 優化器optimizers：優化器optimizers簡介

Day077 訓練神經網路的細節與技巧 - Validation and overfit：檢視並了解 overfit 現象

Day078 訓練神經網路前的注意事項：資料是否經過妥善的處理？運算資源為何？超參數的設置是否正確？

Day079 訓練神經網路的細節與技巧 - Learning rate effect：比較不同 Learning rate 對訓練過程及結果的差異

Day080 優化器與學習率的組合與比較：搭配不同的優化器與學習率進行神經網路訓練

Day081 訓練神經網路的細節與技巧 - Regularization 正歸化

Day082 訓練神經網路的細節與技巧 - Dropout 隨機缺失

Day083 訓練神經網路的細節與技巧 - Batch normalization 批次正規化

Day084 正規化/機移除/批次標準化的 組合與比較：練習時間：Hyper-parameters 大雜燴

Day085 訓練神經網路的細節與技巧 - 使用 callbacks 函數做 earlystop：悔不當初的煞車機制 (EarlyStopping)

Day086 訓練神經網路的細節與技巧 - 使用 callbacks 函數儲存 model：使用 Keras 內建的 callback 函數儲存訓練完的模型

Day087 訓練神經網路的細節與技巧 - 使用 callbacks 函數做 reduce learning rate

Day088 訓練神經網路的細節與技巧 - 撰寫自己的 callbacks 函數

Day089 訓練神經網路的細節與技巧 - 撰寫自己的 Loss function

Day090 使用傳統電腦視覺與機器學習進行影像辨識：了解在神經網路發展前，如何使用傳統機器學習演算法處理影像辨識

Day091 使用傳統電腦視覺與機器學習進行影像辨識：應用傳統電腦視覺方法＋機器學習進行 CIFAR-10 分類

Day092 卷積神經網路 (Convolution Neural Network, CNN) 簡介

Day093 卷積神經網路架構細節：為什麼比DNN更適合處理影像問題, 以及Keras上如何實作CNN

Day094 卷積神經網路 - 卷積(Convolution)層與參數調整：卷積層原理與參數說明

Day095 卷積神經網路 - 池化(Pooling)層與參數調整

Day096 Keras 中的 CNN layers

Day097 使用 CNN 完成 CIFAR-10 資料集

Day098 訓練卷積神經網路的細節與技巧 - 大量數據：資料無法放進記憶體？如何使用Python的生成器generator?

Day099 訓練卷積神經網路的細節與技巧 - 處理小量數據：Data Augmentation 資料增強

Day100 訓練卷積神經網路的細節與技巧 - Transfer learning 轉移學習

Day101 Kaggle期末考

Day102 Kaggle期末考

Day103 Kaggle期末考

Day104 互動式網頁神經網路視覺化

Day105 CNN卷積網路回顧

Day106 常見影像資料集介紹 (Cifar-10, ImageNet, COCO)

Day107 電腦視覺應用介紹 - 影像分類, 影像分割, 物件偵測

-----------------------------------------------------------------------------------------------------



記錄每天學習進度+作業+延伸閱讀時數：


2019/04/16(二) 開始，4/18-5/17上班因素進度落後


2019/05/21(二) 總閱讀時數 5小時 35分，進度 Day19-Day25


2019/05/22(三) 總閱讀時數 5小時 55分，進度 Day26-Day33


2019/05/23(四) 總閱讀時數 2小時 5分，進度 Day34-Day35


2019/05/24(五) 總閱讀時數 3小時 0分，進度 Day36-Day38


2019/05/28(二) 總閱讀時數 1小時 50分，進度 Day39-Day41


2019/05/31(五) 總閱讀時數 2小時 30分，進度 Day42-Day44


2019/06/02(日) 總閱讀時數 5小時 25分，進度 複習 Day1-Day16


2019/06/03(一) 總閱讀時數 3小時 20分，進度 複習 Day17-Day23


2019/06/04(二) 總閱讀時數 4小時 5分，進度 Day45-Day47


2019/06/07(五) 總閱讀時數 2小時 50分，進度 Day48-Day50


2019/06/10(一) 總閱讀時數 3小時 50分，進度 期中考Day51-Day53


2019/06/11(二) 總閱讀時數 2小時 30分，進度 期中考調參


2019/06/13(四) 總閱讀時數 3小時 0分，進度 繼續期中考調參


2019/06/18(二) 總閱讀時數 4小時 20分，進度 Day54-Day56


2019/06/21(五) 總閱讀時數 2小時 15分，進度 Day57-Day59


2019/06/25(二) 總閱讀時數 2小時 25分，進度 Day60-Day62


2019/06/28(五) 總閱讀時數 2小時 15分，進度 Day63-Day65


2019/07/02(二) 總閱讀時數 2小時 30分，進度 Day66-Day68


2019/07/05(五) 總閱讀時數 3小時 0分，進度 Day69-Day71


2019/07/09(二) 總閱讀時數 1小時 50分，進度 Day72-Day74


2019/07/12(五) 總閱讀時數 2小時 45分，進度 Day75-Day78


2019/07/16(二) 總閱讀時數 1小時 30分，進度 Day79-Day81


2019/07/19(五) 總閱讀時數 2小時 30分，進度 Day82-Day85


2019/07/23(二) 總閱讀時數 3小時 30分，進度 Day86-Day88


2019/07/26(五) 總閱讀時數 2小時 25分，進度 Day89-Day91


2019/07/30(二) 總閱讀時數 2小時 15分，進度 Day92-Day94


2019/08/02(五) 總閱讀時數 2小時 10分，進度 Day95-Day98


2019/08/06(二) 總閱讀時數 1小時 50分，進度 Day99-Day100


2019/08/13(二) 總閱讀時數 3小時 10分，進度 Day101-Day103


2019/08/21(三) 總閱讀時數 1小時 40分，進度 Day104-Day107
