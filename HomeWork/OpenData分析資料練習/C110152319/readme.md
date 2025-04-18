# BMI免役體位統計分析（113年）

- C110152319

![png](https://github.com/kerong2002/Nkust-113-2/blob/master/HomeWork/OpenData%E5%88%86%E6%9E%90%E8%B3%87%E6%96%99%E7%B7%B4%E7%BF%92/C110152319/output.png)

## 資料來源
臺北市政府開放資料平台 - 役男徵兵檢查BMI值統計.csv

## 功能介紹
本專案使用 **CsvHelper** 解析 CSV 資料並利用 **LINQ** 進行資料篩選、排序及統計分析。提供以下功能：
- 篩選並提取 113 年的 BMI 值資料。
- 使用 **LINQ** 計算總計免役人數。
- 使用 **LINQ** 計算並顯示平均人數、最大/最小人數，並進行排序。
- 顯示每個 BMI 分類的人數與百分比。
- 計算特定 BMI 分類的總人數（例如 "過重"）。

## 使用套件
- **CsvHelper**: 用於解析 CSV 檔案。
- **LINQ**: 用於資料篩選、排序和統計計算。
