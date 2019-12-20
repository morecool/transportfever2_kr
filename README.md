# Transport Fever 2 Hangeul Translation
## Transport Fever 2 한글화 패치
 - 제작 : 삼류개발자 (coolseed@hotmail.com)
 - 버전 : v0.99-20-001 (2019-12-20) Build 27560
 - 배포 : 디시인사이드 트랜스포트피버 마이너 갤러리 (https://gall.dcinside.com/mgallery/board/lists?id=fever)
 - 소스 : https://github.com/morecool/transportfever2_kr

## 패치방법
### 정품 사용자
 **2019-12-20 27560 패치 이후 한글설정이 삭제되었습니다. 아래 방법으로 하셔야 합니다.**

 - 일단 게임 및 스팀 클라이언트 종료하세요 <- 주의!!
 - **C:\Program Files (x86)\Steam\steamapps\appmanifest_1066780.acf** 파일을 편집기로 열어 아래 부분 수정
 
 ```
	"UserConfig"
	{
		"language"		"english"   <<<<<< 이부분을 
		"language"		"koreana"   <<<<<< 이렇게 수정 (오타 주의 korean 아님 koreana) 27560 패치 이후 안됨
		"language"		"japanese"  <<<<<< **일본어로 셋팅하세요**
	}
```
 - **base-ko.mo, res-ko.mo** 파일을 다운로드 하세요
 
 - base-ko.mo -> base.mo로 파일명 변경하세요!
 - res-ko.mo -> res.mo로 파일명 변경하세요!

 - base.mo, res.mo 파일을 아래 경로에 덮어씌움 (한글경로 말고 일본어 경로에 넣어주세요)

 - **C:\Program Files (x86)\Steam\steamapps\common\Transport Fever 2\res\strings\ja\LC_MESSAGES** 디렉토리로 복사


### 복돌이

 - 설치된 경로의 hlm.ini 파일내에 language부분 수정
 - 다운로드 받은 파일 동일 경로에 복사


## 관련링크
 - mo-to-po : https://ezgif.com/mo-to-po
 - web poeditor : https://localise.biz/free/poeditor
 - POEdit : https://poedit.net/
