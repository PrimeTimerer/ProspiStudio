# PROSPI 26 STUDIO 0.7.391

**게임 2.3.0용입니다.** 공개판 0.7.390 이후의 변경(0.7.391)입니다. 로컬·오프라인 싱글플레이 전용입니다.

English: choose **Language → English** at the bottom of the left menu. Menus, buttons, tabs, card titles and short notes are in English; longer descriptions are still Korean.

## 다운로드와 사용법

- Assets의 **Prospi26Studio.Single.exe**를 받으세요. Source code 압축파일은 실행파일이 아닙니다.
- 0.7.323·0.7.329·0.7.331·0.7.357·0.7.359·0.7.361·0.7.367·0.7.378·0.7.380·0.7.383·0.7.384·0.7.385·0.7.386·0.7.387·0.7.388·0.7.389·0.7.390을 쓰고 있으면 Studio를 켤 때 업데이트 창이 뜹니다(‘지금 업데이트’를 누르면 받고 다시 켬). 0.7.320 이하는 직접 받으세요.
- [전체 사용법](https://github.com/PrimeTimerer/ProspiStudio/blob/main/USER_GUIDE_0_7_391.ko.md) (새 내용은 286장)
- [PDF 사용 설명서](https://github.com/PrimeTimerer/ProspiStudio/blob/main/manual/PROSPI26_Studio_0.7.391_사용설명서.pdf)
- [0.7.159~0.7.391 변경 기록](https://github.com/PrimeTimerer/ProspiStudio/blob/main/CHANGES_0_7_159_TO_391.ko.md)

## 바뀐 것 (0.7.391)

- **빅리그식 타격 타구 현실화 (0.7.391, 클래식)**: 한 경기에 홈런이 너무 많이 나오던 문제(GitHub 이슈 #12)를 손봤습니다. 땅볼·라인드라이브·뜬공 비율을 빅리그 타구 통계에 맞췄습니다. 스틱 중립으로 정타를 맞히면 강한 라인드라이브·땅볼이 많이 나오고, 홈런·장타는 파워 스윙에 스틱을 위로 넣어 정타를 맞힐 때 주로 나옵니다. 빗맞은 뜬공과 이르거나 늦은 스윙은 덜 멀리 갑니다. 빅리그식 타격 설정에 ‘타구 현실화’ 슬라이더(0~150%, 기본 100%)를 더했고, 0%면 이전 분포입니다. PCI(배트 커서) 방식은 바뀌지 않습니다.

예전과 달라지는 점(0.7.390 대비): 빅리그식 타격(클래식)의 타구 분포가 바뀌었습니다(기본 100%). ‘타구 현실화’ 슬라이더를 0%로 두면 예전 분포 그대로이고, PCI(배트 커서) 방식은 같습니다.

## 아직 확인 중인 것

- 빅리그식 타격(클래식): 한 경기 홈런 수와 땅볼·라인드라이브·뜬공 비율이 자연스러운지, ‘타구 현실화’ 0%에서 예전과 같은지
- 자동 업데이트: 0.7.390에서 이번 버전으로의 실제 업데이트

## 파일 확인 정보

- 파일 크기: `100,236,314 bytes`
- SHA-256: `0B22609A6D58718013AFA223ED2C3ECCE320A523328BE75AFBF7AD7F38A64A0A`
