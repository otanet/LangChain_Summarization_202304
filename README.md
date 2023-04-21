# LangChain_Summarization_202304
Here shows you a summarization in Languchain.

LanguChainによる自動要約
〜 ChatGPT部 #02 〜LT大会〜 - connpass 2023年4月15日（土）10:00-11:00

概要:
・LangChainで下記の2つのタイプの自動要約を試してみました。
・芥川竜之介の『蜘蛛の糸』青空文庫(3236文字)を用いました。
・WikipediaのあらすじとLangChainの2種類のあらすじ(要約)を比較し、考察しました。

目次：
1. The map_reduce Chain：並列処理型の自動要約　
2. The refine Chain：翻訳とオリジナルを繰り返す自動要約
上記の1.と2.とで、要約の処理過程を可視化し、プロンプトのテンプレートで調整します。　　　
3. 1.と2.の結果をGraphGPTで可視化
4. 考察・まとめ
5. 参考文献・URL一覧

4. 考察・まとめ
・The refine Chainのテンプレ・カスタマイズがダントツに網羅的でよかった。
・map-reduceの並列処理の要約は、どこか中心がズレやすい傾向が見受けられた。
・GraphGPTのナレッジグラフが比較的、よく捉えていたことにも、驚きが合った。

5. 参考文献・URL一覧
1. 蜘蛛の糸 - Wikipedia https://ja.wikipedia.org/wiki/%E8%9C%98%E8%9B%9B%E3%81%AE%E7%B3%B8 
2. LangChain Summarization 公式ドキュメント 20230414時点 https://python.langchain.com/en/latest/use_cases/summarization.html 
3. LanguChain Summarization Notebook 公式ドキュメント 20230414時点 https://python.langchain.com/en/latest/modules/chains/index_examples/summarize.html 
4. LexRank sumy python library https://pypi.org/project/sumy/ 
5. GraphGPT 20230414時点 https://github.com/varunshenoy/GraphGPT 
6. GraphGPTのアプリ 20230414時点 https://graphgpt.vercel.app/
7. 本slide/PPT https://speakerdeck.com/otanet/tai-tian-bo-san-58f89bcc-07a0-47bf-921b-ab35ec003cca 


