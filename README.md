# taiwanMap 台灣行政區地圖

## 圖資來源

### 縣市界線(TWD97經緯度)

1. 來源：[國土測繪圖資服務雲](https://maps.nlsc.gov.tw/)
2. 檔案名稱：COUNTY_MOI_1090820
3. 資料時間：2023/11/02
4. 備註：

### 鄉鎮市區界線(TWD97經緯度)

1. 來源：[國土測繪圖資服務雲](https://maps.nlsc.gov.tw/)
2. 檔案名稱：TOWN_MOI_1120317
3. 資料時間：2023/04/27
4. 備註：

### 村里界線(TWD97經緯度)

1. 來源：[國土測繪圖資服務雲](https://maps.nlsc.gov.tw/)
2. 檔案名稱：VILLAGE_NLSC_1120317
3. 資料時間：2023/04/27
4. 備註：

## 檔案說明

### county.geojson

> 台灣(全台下所有縣市)

#### 欄位說明

1. type：行政區階層(country→國家、county→縣市、town→鄉鎮市區)
2. ID：編號(戶政司編號，台灣編號則使用00)
3. name：行政區名稱
4. upperLayerID：上一層行政區代號
5. center：行政區中心點
6. data：行政區geojson檔案

### county_xxxxx.geojson 

> 縣市(各縣市下的鄉鎮市區)

#### 欄位說明

1. type：行政區階層(country→國家、county→縣市、town→鄉鎮市區)
2. ID：編號(戶政司編號，台灣編號則使用00)
3. name：行政區名稱
4. upperLayerID：上一層行政區代號
5. center：行政區中心點
6. data：行政區geojson檔案

### town_xxxxxxxx.geojson 

> 鄉鎮市區(各鄉鎮市區下所有村里)

#### 欄位說明

1. type：行政區階層(country→國家、county→縣市、town→鄉鎮市區)
2. ID：編號(戶政司編號，台灣編號則使用00)
3. name：行政區名稱
4. upperLayerID：上一層行政區代號
5. center：行政區中心點
6. data：行政區geojson檔案
