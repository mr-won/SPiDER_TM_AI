## 25.01.10

# SPiDER_TM_AI
SPiDER_TM_AI 정리
![image](https://github.com/user-attachments/assets/3ff8b203-8b47-43f3-aa52-4eabfae26df4)
해킹 및 보안 위협의 지능화로 인하여 사이버 공격은 점점 증가하고 진화하는 추세
공공기관 일일 이벤트와 경보 이벤트는 사람이 처리할 수 있는 한계를 넘어선 상황

인력이 하루에 사고를 처리할 수 있는 건은 하루 60 건 정도로 턱없이 부족한 수치

![image](https://github.com/user-attachments/assets/f6cfb8de-ef2a-4078-b272-dfc5723a151e)
오탐과다처리, 미대응 이벤트 증가, 기술 편차 등의 문제에 직면

![image](https://github.com/user-attachments/assets/c9af42af-a089-4bf3-835e-278633a0a7cd)
지도학습은 IPS, 웹 방화벽 등의 탐지 이벤트의 정확성을 높이는 것을 목적으로 함

비지도학습 알고리즘을 통해 예측한 위험성이 높은 이벤트를 정확하게 탐지하여 기술 편차와 침해사고 대응 시간을 단축

방화벽, web서버의 접속 이벤트에 알고리즘을 적용하여 이상행위를 예측/탐지

통계적 이상탐지기법을 이용하여 악성코드와 같은 비정상행위 탐지

![image](https://github.com/user-attachments/assets/9c6fa67f-a623-4048-a1b2-913c681f1685)

머신러닝 지능형 분석을 통해 고 위험도 이벤트에 대한 집중 분석이 가능하고 실시간 침해 이벤트 자동 분석을 통해
처리범위 확대와 시간을 단축할 수 있습니다.

 IPS, 웹방화벽 탐지 이벤트 -> 지도학습

 방화벽, WEB서버 접속 로그 이벤트 -> 비지도학습

 내부정보 유출과 같은 위협모델을 적용하여 엔드포인트 시스템 장비로 확대 적용

 ![image](https://github.com/user-attachments/assets/1a41f53f-cd46-4e66-89a0-2a313af08283)

지도/비지도 학습 결과에 이글루코퍼레이션 위협 정보 서비스인 이글루 CTI 정보를 결합하여
통합적인 위험도를 제공

이글루 CTI는 KISA의 정보기관과 글로벌 위협과 국내침해사고 정보를 수집하여 100여개의 보안관제 센터에 제공

![image](https://github.com/user-attachments/assets/de6ce9f9-cf42-4ab0-856c-163bbaa4de4c)
지도 알고리즘을 적용한 경보분석 기능은 SIEM에서 수집된 경보이벤트에 대한 지도학습을 통해
심각도와 예측률을 기반으로 이벤트를 분석하여 경보에 대한 빠른 분석을 지원하는 기능

![image](https://github.com/user-attachments/assets/5fae0ae8-b699-487b-9fc9-bcd4aa0b13ac)
비지도학습 알고리즘을 적용한 이상행위 탐지기능은 방화벽, 웹 로그를 기반으로 이상행위를 분석하고 심각도와 예측률을 평가하고
이상치를 시각화로 표출

![image](https://github.com/user-attachments/assets/8f228075-1a12-4f28-a9f9-82a329915d06)
위협 인사이트는 경보 분석과 이상행위 탐지의 분석된 결과들을 종합 위험도로 나타내며, 공격 IP별로 시계열 표출이 가능하다.
상단의 시각화된 위협을 클릭하게 되면 위협이 연관된 정보들을 같이 표춣아ㅕ 공격간의 연관성을 보다 쉽게 분석

![image](https://github.com/user-attachments/assets/3c20c59a-4ded-4b2b-872b-2b1c3da31240)
위협 인사이트에서 분석된 경보를 상세하게 보는 경우 연관 정보 및 시계열 분석과 KILL-CHAIN 분석을 통해 보다 직관적인 위협 분석 
환경을 제공

<< 시스템 도입에 따른 기대효과 >>
경보 자동화 분석을 통해 효율성이 증가하고
이상행위 탐지를 통해 알려지지 않은 보안위협이 감소 효율성 증가
















![image](https://github.com/user-attachments/assets/064dc765-aa92-4532-88f0-4bae6876b4c9)
SPiDER TM AI Edition의 메뉴는 SPiDER TM 5.0의 인공지능 분석이라는 이름으로 함께 있습니다.

인공지능 분석 요약, 위협 인사이트, 이벤트 분석, 이상행위탐지, 이벤트 통계 분석으로 총 5개로 구성되어 있습니다.

인공지능 분석 요약은 현재를 기준으로 24시간 동안의 데이터를 보여주는 대시보드 메뉴입니다.

이 화면에서 사용자는 전반적인 보안 현황을 확인할 수 있습니다.

![image](https://github.com/user-attachments/assets/47faddf9-9322-4639-bdac-6b25422b34c0)
위협 인사이트는 이벤트 분석과 이상행위탐지 데이터를 기반으로 위험도를 재산정하여

가장 위험한 출발지를 위험도 순으로 보여줍니다. 

![image](https://github.com/user-attachments/assets/76f52ada-153c-420a-ae8a-deadec22d794)
출발지 IP에서 우클릭을 통해 추가분석 메뉴를 불러올 수 있고 위협 인사이트 상세 분석하기 메뉴를 통해 연계분석 화면을 볼 수 있습니다.

![image](https://github.com/user-attachments/assets/ba700ff1-65e6-4322-8415-2653e4992d42)
위협인사이트 상세 메뉴는 해당 IP의 이벤트 분석 결과와 이상행위 탐지 결과를 연관지어 시간 흐름에 따라 발생 빈도를 표현 해주며

![image](https://github.com/user-attachments/assets/d9f2521b-2b6c-4e68-b844-9edf4afe80bd)
사이버 킬체인도 함께 보여줍니다.

![image](https://github.com/user-attachments/assets/66fbd3f9-945d-4762-852e-172d8355b08a)
다음은 이벤트 분석입니다.
이벤트 분석은 지도학습을 기반으로 탐지 장비의 정오탐을 위험도별로 구분하여 주며 인공지능 예측결과를 분석하고 우측 상단의 피드백을 통해
모델에 재반영할 수 있습니다.

![image](https://github.com/user-attachments/assets/f4d49721-8238-4c80-90b3-82448749e24a)
이상행위 탐지 메뉴입니다.
이상행위 탐지는 보안장비에서 탐지하지 못한 이상행위를 인공지능이 알고리즘을 통하여 예측한 결과를 보여주는 메뉴로
Sankey Chart와 네트워크 시각화를 통해 다양한 분석이 가능합니다.

![image](https://github.com/user-attachments/assets/b664cacc-7b21-44a4-9d03-8c57b953cc11)
이벤트 통계분석입니다.
이벤트 통계분석 메뉴는 지도학습의 결과를 로그 타입별 장비별 공격명 별로 분석하는 메뉴로 클릭을 통해 해당 통계치의 이벤트를 분석할 수 있습니다.



