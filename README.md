# Mabinogi Multi Helper

마비노기 클라이언트를 CPU 분배로 다클라 성능 향상

- 이 프로그램은 다중 클라이언트 환경에서 마비노기의 CPU자원을 조절하여
- 좀 더 낮은 CPU사용량과 낮은 전력을 사용하도록 도와주는 프로그램입니다.

(Mabinogi CPU preferrence divider for lower usage of CPU and more less power consumption. )


refer : <https://cafe.naver.com/mabinogidsg/642329>

## Build & Test Environment

```Text
OS : Windows 10 Pro 64bit 20H2

Build : Visual Studio 2019

.Net Framework : 4.0
```
## TODO
  - 예약종료 된 후 화면에 출력중인 프로세스 목록을 즉시 갱신하기 (운 나쁘면 종료 후 최대 5초 뒤 반영 됨)


## Change Log


```Text
2021-06-14
    - 프로세스 숨김/보이기 기능
    - 프로세스 예약 종료 기능 추가
    - 시스템 예약 종료 기능 추가
    - 소스코드 최적화
    - BackgroundTaskManager 버그 수정
2021-06-11
    - add background task manager
2021-06-08
    - add trayicon
    - set activity window
    - memory GC fix
    - auto refresh process list
    - check same process is running
    - Re-design Program icon
    - add Program info dialog ( To show Program Version & Download Link, developer )
    - When application closing, ask to user whether close or put tray-icon.
    - Add ReleaseNote.txt for Normal Users.
    - Source Code relocate ( folder , namespace , ... )
    
    
    
##############이 아래 글자 수정 금지####################    
^^#$[TestValue]^^#$[3]
    
```
