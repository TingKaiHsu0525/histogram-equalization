![Static Badge](https://img.shields.io/badge/passing-gray?label=build&labelColor=gray&color=green) ![Static Badge](https://img.shields.io/badge/53%25-gray?label=Verilog&labelColor=gray&color=violet) ![Static Badge](https://img.shields.io/badge/36.9%25-gray?label=Jupyter&labelColor=gray&color=orange) ![Static Badge](https://img.shields.io/badge/10.1%25-gray?label=Python&labelColor=gray&color=navy)

# histogram-equalization

*  原始圖形
  
  ![image](https://github.com/TingKaiHsu0525/histogram-equalization/assets/145333999/3bcfb296-baba-439c-811d-bb1232f5dced)


## 功能
*  使用verilog實現直方圖等化
*  使用testbench檢驗功能正常
*  Synthesis模擬預計使用面積(Area)、時間(Time)、功率(Power)
*  Pre-sim檢測電路功能正常
*  Primetime模擬更詳細的使用時間(Time)、功率(Power)

## 結果
*  輸出圖形

  ![image](https://github.com/TingKaiHsu0525/histogram-equalization/assets/145333999/a04d47c9-f247-47ee-bc93-c1f76a48a0f7)
*  直方圖等化前後對比
  
  ![image](https://github.com/TingKaiHsu0525/histogram-equalization/assets/145333999/8f24522c-79f6-4e44-8b0f-981d1f76aab2)

*  Modelsim
    *    波形(Waveform)
   
      ![image](https://github.com/TingKaiHsu0525/histogram-equalization/assets/145333999/4e104530-9c12-4756-929c-460d2fccc862)
    *    直方圖記憶體(Histogram Memory)
      
      ![image](https://github.com/TingKaiHsu0525/histogram-equalization/assets/145333999/9036e904-3f24-4893-a6c1-513bbb7a9e60)
    *    累積分布函數記憶體(CDF Memory)
     
      ![image](https://github.com/TingKaiHsu0525/histogram-equalization/assets/145333999/3cadcae0-4b80-4b1d-bf40-bf99cd9e6469)
    *    轉換表格記憶體(Transformed Table Memory)
      
      ![image](https://github.com/TingKaiHsu0525/histogram-equalization/assets/145333999/e520a05f-37f5-4d75-877c-7c7953abe642)

*  Synthesis
    *    面積(Area)
   
      ![image](https://github.com/TingKaiHsu0525/histogram-equalization/assets/145333999/391b32f3-9cc1-4d6d-b55d-0e7a7d7b235a)
    *    時間(Time)
  
      ![image](https://github.com/TingKaiHsu0525/histogram-equalization/assets/145333999/96129573-cefe-4123-91e3-6f1c5ac0c133)
    *    功率(Power)
   
      ![image](https://github.com/TingKaiHsu0525/histogram-equalization/assets/145333999/2d0615bf-a854-409d-8c8c-bfb3a25c0fb3)
*   Pre-sim
  
  ![image](https://github.com/TingKaiHsu0525/histogram-equalization/assets/145333999/c2b4d851-4ccb-4f5d-8863-ad2bdebc4589)
*   Primetime
    *    時間(Time)
    
      ![image](https://github.com/TingKaiHsu0525/histogram-equalization/assets/145333999/c3b25da8-1f0a-4876-8aa3-4ae2fd0e5286)
    *    功率(Power)
      
      ![image](https://github.com/TingKaiHsu0525/histogram-equalization/assets/145333999/9200cb80-ab93-49b6-9725-92acf9c96a91)
