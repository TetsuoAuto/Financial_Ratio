這份練習的目的在於獲得指定股票一段時間(三年)內的財務比率趨勢圖，並做經營的不同面相分析。

心得:

一.由於我是使用jupyter notebook撰寫python程式。完成的成品多為ipynb檔，在python上無法直接被其他ipynb檔引用。
後來參考"https://www.itread01.com/content/1544369431.html"
內提供的Ipynb_importer.ipynb解決，成功import上次撰寫的Season_FinancialStatement.ipynb。

問題解決: 和網站上說明不同的是，並非直接import Ipynb_importer就可以使用因為他本身也是一ipynb檔無法被import,需要以%run Ipynb_importer.ipynb的方式跑動才可以import其他ipynb檔。

二.這次與其說是python的練習，其實更像是各項財務比率的複習。運用各種不同比率能分析公司在獲利能力，償債能力，以及成長性方面是否健全。

三.五力分析若沒有加上一段時間段或和其他同業比較並沒有辦法了解是否本身好壞。這次我加上一段時間段(三年)分析一間公司在這段時間內的比率趨勢，做為公司的內部管理分析。

四.matplotlib圖表顯現無法使用中文標籤，將出現口口口等亂碼。目前解決方法是將中文標籤和英文標籤作為一個dictionary，圖表顯現時使用英文部分作為標籤。
