# About us.

## Abstract

산림청의 2021년도 산불통계 연보에 따르면 최근 10년간 산불로 인한 피해 면적은 급격하게 증가함. 그럼에도 불구하고 현재 산불 발생 시 재난관리 목적으로 민간에 공개되는 관련 정보로는 산림청 산불 상황 관제 시스템의 발원지 중심적인 점 형태로 된 데이터만이 공개됨.
따라서 본 연구에서는 화재의 진행 상황을 알 수 없었던 불편함을 파악하고 이를 해결하고자 함. 이를 위하여 Suomi NPP와 NOAA-20위성에 탑재된 VIIRS 정보를 포함하는 시스템 인터페이스(API)와 산림청 산불피해대장의 자료를 활용하여 산불의 진행 상황 정보를 확인 할 수 있도록 구현하였음.
본 연구의 결과물은 머신러닝을 이용한 밀도기반 군집분석(DBSCAN)으로 산불 의심 구역을 탐색하고, Convex Hull 알고리즘을 통해 Polygon 형태의 GeoJSON 포맷으로 출력 및 Database화 되며 GIS 기반으로 Web을 통해 시각화 하여 산불상황 시 대피를 위한 의사결정 참고 정보를 제공함.

(Below is the machine-translated abstract)
According to the Forest Service's 2021 Forest Fire Statistics Yearbook, the area affected by forest fires has increased rapidly over the past 10 years. Nevertheless, only data in the form of a point centered on the origin of the Forest Service's forest fire situation control system is disclosed as related information disclosed to the private sector for disaster management purposes in the event of a forest fire.
Therefore, this study aims to identify and solve the inconvenience of not knowing the progress of the fire. To this end, the system interface (API) including VIIRS information mounted on Suomi NPP and NOAA-20 satellites and data from the forest fire damage register of the Korea Forest Service were used to check the progress information of the forest fire.
The results of this study are DBSCAN using machine learning to explore suspected forest fires, output and database in the form of GeoJSON in the form of Polygon through Convex Hull algorithm, and visualized through the web based on GIS to provide decision-making reference information for forest fires.

## Link : [FLCS_Demo](http://14.54.11.248:8080/FLCS/FLCS_Main.jsp)

## Introduction Video : [Full](https://youtu.be/i0T7D0HggxE), [Short](https://youtu.be/r57d8KcvtAg)

## Introduction Presentation : [Link](https://github.com/Ewonhee/FLCS/blob/main/etc/%EB%B3%B4%EC%B6%A9%EC%84%A4%EB%AA%85%EC%9E%90%EB%A3%8C_%EC%A0%84%EC%B2%B4.pdf)

## Data Validation : [Link](https://github.com/Ewonhee/FLCS/blob/main/etc/%EB%8D%B0%EC%9D%B4%ED%84%B0_%EA%B2%80%EC%A6%9D.pdf)
<br>

# FLCS Development Environment

|System|Name|
|-|-|
|DB|MySQL Server 5.7|
|DataProcess|Python 3.10.x|
|Backend|Java 9.0.4(JSP)|
|IDE|Eclipse IDE for Enterprise Java and Web Developers(2021-12, 4.22.0)|
|IDE|Visual Studio Code (Always newest version)|
|VCS|GitHub(SourceTree 3.4.8, Fork1.74.1.0)|

# License

This project is licensed under the terms of the MIT license.
