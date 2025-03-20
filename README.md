⭐️ 전북대학교 캡스톤 팀 프로젝트에서 기여했던 것을 구분하기 쉽게 분리한 레포 입니다.

<br>

![리틀워 썸넬](https://github.com/user-attachments/assets/b1cb913a-72f7-41e1-885e-0c6e11d7adad)

<br>

# 프로젝트 개요
| 개발 환경 | Unity |
|:------:|:------:|
| 개발 기간 | 2024/03/07 ~ 2024/05/03 |
| 게임 설명 | 타워 디펜스 |
| 담당 역할 | 타워 시스템에 대한 전반적인 개발 |
| 팀 레포지토리 | [GitHub](https://github.com/gdevhun/LittleWar) |
| 스케줄링 | [Notion](https://river-pearl-643.notion.site/CapstoneTeamProject-de3a45a7dabe47f3b3bb3645cffc6a8d?pvs=4) |

<br>

# 시연 영상  
+ [Little War](https://youtu.be/OogcS3r93f4)

<br>

# 주요 기능  
⚡ 타워
- Tower Base : 모든 타워 공통 멤버 정의 [[스크립트](Tower/Base/TowerBase.cs)]
- ArcherTower Base : Tower Base 상속 ⇒ 아쳐 타워 공통 멤버 정의 [[스크립트](Tower/Base/ArcherTowerBase.cs)]
- MagicTower Base : Tower Base 상속 ⇒ 매직 타워 공통 멤버 정의 [[스크립트](Tower/Base/MagicTowerBase.cs)]
- Tower Implement : 각 타입의 타워를 상속 받아 구현 [[스크립트 폴더](Tower/Implement)]
- TowerManager : Tower Base 참조 ⇒ 타워 설치, 해제, 업그레이드 관리 [[스크립트](Tower/Manage/TowerManager.cs)]
- ![타워 클래스 다이어그램final drawio](https://github.com/LeeJungHwi/LittleWar_./assets/101587101/a45e2465-4c1d-4445-901a-6ddb3e7d89b4)
