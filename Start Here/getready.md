# Power Automate 흐름 생성을 위한 사전준비

## 1. Office365에서 Power Platform 접속 및 흐름 생성

[오피스365 사이트](https://www.office.com)

-위 사이트에 접속 후, 발급받은 office 365 학생 계정으로 로그인 해줍니다

-아직 학생계정 발급이 안되었다면

[학생계정 발급](/M365.md)

위 과정을 먼저 해주세요!


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/6047f537-47a7-42f5-8b4b-56004d69ee21)


로그인 후, 좌측 상단 와플모양 버튼 클릭 

-> Power Automate 로 접속해주세요


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/ff58840f-5bc3-458a-a969-d9d472ae3406)


좌측에 보이는 '만들기' 메뉴를 클릭해주세요


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/e187f063-025f-4bda-b4ba-098388f093b6)


자동화된 클라우드 흐름 만들기 클릭해주세요


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/d2554471-b5a5-417b-9032-c0c320e88f0b)

흐름 이름 : 동아리 모집

흐름 트리거 검색 : 새 응답이 제출되는 경우

해당 설정이 끝나셨다면, 만들기 클릭!


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/5585a718-0bfd-4309-bac5-d1fb204dde00)


이렇게 화면이 뜨신다면, 우측 상단의 새 디자이너 옵션을 꺼주시고,


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/b7535216-118d-4e1c-8e30-e744e94cfebe)


아래와 같은 화면이 뜬다면 정상적으로 진행된 것입니다.


## 2. 흐름 트리거용 Form 만들기

![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/1985d970-c42c-45de-ace6-029010dba7a4)


위 서비스 중 Forms에 접속해주세요. 아래 링크로 접속해주셔도 됩니다.

[폼즈 사이트](https://forms.office.com/)


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/d6b495b6-31c8-4db0-b028-bb2de4ef93c3)


위 버튼 중 새 양식을 눌러서 폼을 만들어주세요


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/c4c1ffb7-43bf-42e1-a101-3343840ea5e1)


참가자 이름, 학과, 참가자 이메일, 참가일, 지원동기 순으로 항목들을 추가해주세요. 

참가일은 '날짜' 항목으로, 나머지는 '텍스트' 항목으로 추가해주시면 됩니다


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/a99ee8fc-8cad-49df-9408-0b7ed0de1d3d)

(참가일 추가한 모습)

![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/aae1c336-7807-4c19-9b91-011b193be853)


이렇게 되셨다면 Form 완성입니다!


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/16f347e3-226d-48ec-8116-d1552fd7c182)


참고) 첨부한 엑셀파일에 흐름이 진행되는 동안 해당 폼 데이터가 추가될 예정입니다.


## 3. Sharepoint 내 사이트 만들기

![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/03e80b1b-22f4-4cbd-936f-ac18f8c39f42)


sharepoint 서비스로 접속해줍니다


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/0e32f310-051e-4a6f-b3bd-dba371fca49f)


좌측 상단의 사이트 만들기 를 클릭해줍니다


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/80aac864-a6b5-4744-8fc6-d5334260813a)


팀 사이트를 선택해줍니다


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/d5f60492-2794-4f06-ae18-dda9f1dde66f)


템플릿을 Standard template 으로 선택해줍니다


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/8898bee3-e65a-4d32-a9ce-392d12bc38f4)


템플릿 사용 버튼을 눌러줍니다


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/8f850177-7085-4dd0-b40e-d6e07b6a3bfc)


Site name : Knu Club 입력 후에

Next 버튼을 클릭해줍니다


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/33f8213f-37ed-4322-be9c-eddca6eb36de)


언어설정은 한국어로 설정해줍니다

-> 하단에 사이트 생성 버튼을 클릭해줍니다


![image](https://github.com/SangYoupLee/PowerPlatform/assets/125184499/38d24eb2-007a-40c2-a635-05e8f70e87c6)


멤버 추가 따로 없이 바로 사이트 생성을 완료해줍니다

이로써, 흐름에 사용할 팀 사이트 생성을 완료했습니다.


## 4. 라이브러리 및 실습 시 사용 파일 업로드


