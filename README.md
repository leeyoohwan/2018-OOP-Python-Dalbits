# 2018-2 객체지향 프로그래밍 프로젝트 - **{Dalbits}**
구성원: 2-3 이유환 | 2-4 경다녕 | 2-6 배상우

## 1. 주제
우리 학교에서 활용이 가능한 인공 비서 ‘Dalbits’ 제작

## 2. 동기
세종과학예술영재학교에서 생활 하면서 효율적인 시간관리가 아주 중요하다는 것을 많이 느끼지만 이를 실천하기는 상당히 어렵다. 이에 학교 생활을 하는데 시간을 효율적으로 관리하는것을 도와줄 수 있는 프로그램이 있다면 좋을 것이라고 생각했다.

## 3. 프로그램 사용 대상
이 프로그램은 달빛학사에 관련된 기능들이 다수 계획되어 있기 때문에 달빛학사 접근 권한을 가지고 있는 세종과학예술영재학교 학생들을 대상으로 개발할 예정이다. 

## 4. 목적
내신 공부부터 여러가지 과제, 프로젝트, 공지 확인 등 확인하고 신경써야 할 것이 많은 세과예영 학생들에게 시간관리를 도와주는 마치 영화 ‘아이언맨’에 나오는 자비스와 같은 비서 프로그램을 제작해 보고자 한다. 일정과 알림 확인을 한 번에 진행하고, 소학습실 신청과 같은 반복 작업을 편리하게 자동화시킴으로써 학생들의 생활에 직접적인 도움이 되도록 프로그램을 제작하고 최종적으로는 학생들에게 프로그램을 배포해보고자 한다.

## 5. 주요기능
- 새로 올라온 공지 알림, 제목 / 링크(관심있는 제목이면 링크 출력말고 직접 url 열어주는 기능)
- 새 메시지 확인 및 메시지 보내기
- 소학습실 신청(동료신청 기능도)
- 스케쥴러(오늘 할일 메모)
- 오늘 아침/점심/저녁 메뉴는? 식단표 확인
- 오늘 할일 목록 출력
- 공강시간에 할 수 있는 여러 일들을 적어놓고 랜덤하게 할 일을 하나 추천해주는 기능
- 하루에 공부한 시간 측정 그 후 그래프로 표현까지 → 날짜별로 정리해 간단한 통계 출력


## 6. 프로젝트 핵심
새로 올라온 공지 제목을 출력해주는 기능이나 소학습실 신청, 급식 메뉴 출력 등 달빛학사 사이트에 접속하여 사용하는 기능이 여러가지 포함되어 있기 때문에 세션을 적재적소에 효율적으로 사용하는 방법이 필요할 것으로 보인다.

## 7. 구현에 필요한 라이브러리나 기술
GUI를 구현하기 위해 pyqt부터 시작하여 달빛학사의 여러가지 웹 데이터를 파싱하기 위한 beautifulsoup부터 하루에 공부한 시간을 그래프로 표현하는 기능을 구현하기 위해서 matplotlib을 사용하는 등 여러가지 라이브러리가 사용될 것이다.

## 8. **분업 계획**

## 9. 기타
