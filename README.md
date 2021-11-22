# 21_Caerang_SwExhibition

## 개요     

본 프로젝트는 세포 검출 결과 이미지를 이용한 세포 계수를 지원하는 웹 페이지 제작 프로젝트이다.    
오늘날 인간의 업무 중 반복적이고 정적인 작업은 대부분의 영역에서 기계의 역할로 대체되어 왔다.    
하지만 의료 분야에서만큼은 기계의 도입이 조심스럽고 이로인해 아직도 사람의 손을 거쳐 시행되는 작업들이 있다.     
세포의 수와 그 형태를 파악하는 것은 필수적이고도 중요한 작업이다.    
따라서 사람마다의 다른 기준에 따른 문제, 시간적, 효율적인 문제를 해결해보고자 본 프로젝트를 시행한다.     

## 도구   

<div>
  <image src=img/streamlit2.png width=300 height=200>
  <image src=img/flask.png width=250 height=200>
    </div>

* Streamlit   
사용자의 의도와 기획에 맞는 웹 프레임워크가 존재하는데 이번 프로젝트에서는 Streamlit을 사용한 웹 페이지 제작을 진행했다.   
Streamlit은 기계 학습과 데이터 과학을 위한 오픈 소스 웹/앱 프레임워크이다. Python을 이용하며 간편하고 쉽게 웹 페이지 제작이 가능하다.

* Flask   
Flask는 python기반의 오픈 소스 웹 프레임워크이며, 다른 웹 프레임워크에 비해 비교적사용하기 편리하다는 장점을 가지고 있다.  
이를 통해 서버와의 통신을 가능케 하고 데이터를 주고받는다. 

## 설명     
1. streamlit을 통해 이미지 업로드 
2. 서버로 이미지 전송  
3. 서버에서 flask로 이미지 받아 저장
4. 학습된 모델에 넣어 셀 검출 후 반환   
    
-----
    
     메인 페이지   
<img width="800" alt="1" src="https://user-images.githubusercontent.com/52690009/142859567-f39398a7-bcd9-470c-b5b5-43e75a87cbf7.png">


    이미지 선택
<img width="800" alt="2" src="https://user-images.githubusercontent.com/52690009/142859682-e32dacd3-6ab9-4f63-9c4c-88a01ead062b.png">

    Detection
<img width="800" alt="4" src="https://user-images.githubusercontent.com/52690009/142859695-639da905-c132-40c4-80fa-e2e1ec84c38d.png">
    
    Result
<img width="800" alt="5" src="https://user-images.githubusercontent.com/52690009/142859702-99d40bda-10e0-4862-8956-f432655f1222.png">
    
    
    
