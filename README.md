# Well Log Petrophysical Interpreter

114 學年度井測期末作業 — H-8 Well

**互動網頁：https://charliebai605.github.io/well-log-petrophysics/**

## 使用方式

1. 開啟上方網址
2. 點 **Choose LAS File** 上傳 LAS 檔案
3. 調整左側參數（或使用預設值）
4. 點 **Calculate & Plot** 產生圖表

## 計算區間

H-8 Well，500–600 m

## 計算項目

| 題目 | 方法 | 關鍵參數 |
|------|------|---------|
| Q1 Vshale | Linear GR | GR_min=60, GR_max=135 gAPI |
| Q2 PHIE | Density porosity + shale correction | RHOMA=2.65, RHOF=1.05 g/cm³ |
| Q3 Sw | Archie | Rw=1.57 ohm·m, a=1, m=2, n=2 |
| Q4 綜合解釋 | Vsh + PHIE + Sw cutoff | 潛力砂層：530–535 m, 556–557 m |

## 檔案說明

| 檔案 | 說明 |
|------|------|
| `welllog_interpreter.html` | 互動式網頁程式（方案 B） |
| `Q1_Vshale.png` | 第一題：Vshale 深度剖面 |
| `Q2_Porosity.png` | 第二題：PHIT / PHIE 深度剖面 |
| `Q3_Sw.png` | 第三題：水飽和度深度剖面 |
| `Q4_combined_plot.png` | 第四題：五道綜合解釋圖 |
| `H-8_Suite2_Run2_...las` | 原始井測資料 |
