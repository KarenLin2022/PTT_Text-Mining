# Sentiment-analysis_PTT
**論文名稱**  

偵測憂鬱傾向者情緒狀態：以機器學習分析PTT電子佈告欄文章  
Detection of Mood State of People with Depression: Analyzing PTT Bulletin Board System Articles by Machine Leaning  

**論文摘要**  

本研究的目的是希望藉由分析社群媒體資料對有憂鬱傾向者有更多的了解，尤其其中可能包含從未接觸過精神醫療服務的使用者，並希望運用機器學習技術增進精神醫療臨床實務效益。
本研究的方法是以社群論壇「批踢踢實業坊」(PTT)作為文本資料來源，共92,273筆，並以人工標註出有表達自殺意念的365筆資料。運用機器學習技術建立有憂鬱傾向者的情緒狀態偵測模型(偵測是快樂或悲傷)和自殺意念偵測模型。並以獨立樣本t檢定和卡方檢定分析文本資料，以了解有和無憂鬱傾向者於普遍性、快樂和悲傷情緒狀態，以及表達自殺意念時的文本特性差異(包含發文時間、人稱代名詞使用頻率和發文字數等變項)。
本研究的結果顯示情緒狀態偵測模型預測能力可達AUC(Area Under the Receiver Operating Characteristic Curve) = .889。而自殺意念偵測模型預測能力可達AUC = .964，但AUPRC(Area Under the Precision-Recall Curve) = .315，顯示該模型對於偵測有自殺意念的使用者預測能力較低，但因臺灣尚未有相關研究，本研究的初步探索可供借鏡。而有和無憂鬱傾向者的文本特性差異分析結果顯示於發文時間、人稱代名詞使用頻率和發文字數有明顯差異，並且於快樂情緒狀態時的差異較大，但表達自殺意念時的差異不明顯。本研究結果未來可能運用於早期偵測和心理衡鑑資訊蒐集，以及追蹤治療後情緒變化，以協助臨床決策判斷等。但本研究因受限於難以取得適當且足夠的自殺相關文本資料，相關分析結果待後續研究進一步檢驗和改善。
*關鍵字*：憂鬱、情緒、自殺意念、社群媒體、機器學習。


**Abstract**  

The purpose of this study was to have a better understanding of people with depressive tendencies by analyzing social media data, especially some data probably from users who never had contact with psychiatric services. Another aim was to use machine learning techniques to improve the efficiency of psychiatric clinical practice.
This study’s data were from the internet forum “PTT” with a total of 92,273 articles. Among these, there were 365 annotated articles expressing suicide ideation. This study used machine learning techniques to build the “Mood state detection model” (detection of happy-sad mood) and the “Suicide ideation detection model” for people with depressive tendencies. And this study analyzed data with variables of the timing of texts, frequency of personal pronoun use, and word counts by independent t-test and chi-square testing to know the difference of textual features between people with and without depressive tendencies in general, happy, sad, and suicide-ideation states.
The results of this study were that the mood state detection model’s AUC(Area Under the Receiver Operating Characteristic Curve) = .889. And the suicide ideation detection model’s AUC = .964, but AUPRC(Area Under the Precision-Recall Curve) = .315. It means this model has low predictability for suicide ideation of people with depressive tendencies. However, there is no related research in Taiwan, the preliminary exploration of this model can be for future reference. The statistical results show there were significant differences of textual features between users with and without depressive tendencies in the timing of texts, frequency of personal pronoun use, and word counts, especially when users were expressing happy feelings, but no significant differences when users were expressing suicide ideation. The results of this study have the potential to be early detection tools, help collect information for psychological assessment, and track emotion trends after medical therapy for enhancing clinical decision-making. However, this study couldn’t get enough representative data about suicide ideation, related results need to be further inspected and improved by follow-up research.
*Keywords*: Depression, Mood, Suicide ideation, Social media, Machine learning
