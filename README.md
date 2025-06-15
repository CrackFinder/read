# 프로젝트 안내
## 프론트엔드
1. 저장소 클론
```bash
git clone <git 주소>
```
2. 의존성 설치
   - 터미널 열기(Ctrl + Shift + `)
   - 프로젝트 루트에서 실행
```bash
npm i
```
3. 개발서버 실행 `npm run dev`

> 완료된 기능
> - 디자인: 데스크톱 화면 기준 완성
> - 서버연동 : 로그인/회원가입 API 호출
 
> **참고**  
> 반응형은 현재로서 필요없다 판단  
> (실제 사용 시, 스마트폰으로 들고 다니며 포트홀 확인은 어려울 것으로 예상됩니다.)

---
## 백엔드
1. 저장소 클론
```
git clone <Git 주소>
```
2. 의존성 설치
   - IDE에서 `from … import …` 오류가 발생하면, 터미널에서 아래 명령어 실행
```bash
pip install -r requirements.txt
```
> **변경 사항**  
> 백은 현재 변경된거없습니다.   
> 프론트와 연동시 422 에러가떠서 코드한줄 추가해서 에러잡았습니다.

## DB
flask에서 사용되는 db는 sqlite입니다.  
flask 파일보시면은 instance 파일안에 users.db가 있습니다.
GUI형태로 데이터 확인하고 싶으시면
```
https://sqlitebrowser.org/
```
사이트 들어가셔서 다운로드하시면 됩니다.
따로 설정할거 아예없고, 
1. 파일 클릭
2. 데이터베이스 열기
3. 데이터 파일 삽입
4. sql 구문사용해서 데이터확인

## 현재까지 사용한 기술스택
**front** : react, typescript, tailwind, zustand, tanstack query, axios  
**back** : flask, sqlite


7월 2일 작업시작한다고 알고있습니다.  
그전에 아이소핑크를 활용해서 도로 구현하고, 라즈베리 자율주행 끝내는거로 목표로 잡겠습니다.

다들 시험 화이팅하세요 *⸜( •ᴗ• )⸝*
