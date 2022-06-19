# Poem-Karaoke

- [설치 및 실행](#설치-및-실행)
- [설계](#설계)
- [기능](#기능)
- [구현](#구현)
- [트러블 슈팅](#트러블-슈팅)

## 설치 및 실행
## 설계
### 목표
- `react`를 사용해 기존 **[포트폴리오 사이트](https://cargocollective.com/suhyouri)** 이사하기 
- [Speech-to-Text](https://cloud.google.com/products?hl=ko)(voice recognition)을 사용해 시 노래방 Static 사이트 만들기 

### 사용

| -             | Link                                                            |
|---------------|-----------------------------------------------------------------|
| Lang          | [react](https://reactjs.org/)                                   |

### 조사 필요

(1) 포폴이사 
- Sidebar고정으로 화면상 오른쪽만 바뀌도록 

(2) Poem-Karaoke 
- Speech-to-text CSS Effect & Free Service 
- 실시간 연동(새로고침해도 현재 누군가가 읽은 곳에서) 
 
### 레이아웃

- 헤더
- 사이드바 
- 썸네일 그리드 
  - 글 제목, 년도
- 푸터

![](/docs/layout.png)


## 트러블 슈팅
