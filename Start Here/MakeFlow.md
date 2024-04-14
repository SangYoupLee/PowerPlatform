# 클라우드 흐름 만들기

## 흐름으로 이동


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/1741eb58-505f-440e-9da0-d5452ceb2dfe)


[파워 오토메이트 사이트](https://make.powerautomate.com/)

Power Automate 사이트로 들어가서, 이전에 getready.md 에서 만들어준 흐름으로 이동합니다


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/efaa02b4-13d9-4fba-bef3-0c633e2119a6)


"동아리 모집" 이라는 흐름이 있을거에요! 해당 흐름을 눌러서 열어주세요


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/01d11ce6-73fd-426d-bdb3-0cf54402dde3)


이후 좌측 상단의 [편집] 을 눌러서 흐름 편집화면으로 이동합니다.


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/7361db2b-949d-4068-a7a4-22b9238d8c3b)


우측 상단의 [새 디자이너] 를 눌러서 꺼줍니다. 해당 흐름은 완성된 흐름입니다.

우리는 Forms, Sharepoint, Excel, Onedrive, Outlook 해당 다섯가지 커넥터를 사용할 예정입니다.

따라서, 해당 서비스 관련하여 권한을 요청할 수 있는데 당황하지 마시고 모두 동의 눌러주시면 됩니다 :)


## 1. 새 응답이 제출되는 경우


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/10609b01-eaf3-4dae-a710-b746d73e67bd)


트리거 내에 드롭다운 메뉴를 눌러서

양식 ID는 이전에 만든 '동아리 모집' 폼을 선택해줍니다


## 2. 응답 세부 정보 가져오기


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/44b22aa8-ace8-45b2-9e99-d7984de4c85c)



"새 응답이 제출되는 경우" 트리거 아래에 + 버튼을 눌러 [작업 추가]를 눌러줍니다.


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/b17d21ec-cb60-4885-9116-7e1997afcdae)


검색창에 '응답 세부 정보' 까지만 입력하시면 '응답 세부 정보 가져오기' 액션이 나타날 거에요

'Forms' 를 입력 후 해당 커넥터를 클릭해주면 좀 더 쉽게 찾을 수 있습니다 (Ctrl + F) 활용해도 좋아요!


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/8a9f3621-b027-494d-9370-f0ef573bb8c7)


이전 트리거와 동일하게, 

양식 ID도 '동아리 모집' 으로 해주시면 됩니다

이후 응답 ID 는, 우측 하단에 '동적 콘텐츠 추가' 를 눌러준 뒤 응답 ID를 선택해주시면 됩니다


## 3. 테이블에 행 추가


이전과 똑같이 작업을 추가해줍니다 "테이블에 행 추가" 를 찾아서 추가해주세요


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/4266ddef-6c77-4e4e-a9aa-00160e65b754)


위치 : "Group - KNU Club" (우리가 만든 Sharepoint 내 팀 사이트 이름)

문서 라이브러리 : "My Meetup"

파일

테이블

