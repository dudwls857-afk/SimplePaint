# (C# 코딩) SimplePaint


## 개요
- C# 프로그래밍 학습
- 1줄 소개: 마우스를 이용하여 도형을 그리고 색상과 선 두께를 설정할 수 있는 그림판 프로그램

- 사용한 플랫폼: 
  - C#, .NET Windows Forms, Visual Studio, GitHub

- 사용한 컨트롤:
  - Label, Button, ComboBox, TrackBar, PictureBox, GroupBox

- 사용한 기술과 구현한 기능:
  - Visual Studio를 이용하여 UI 디자인
  - enum을 이용한 도형 선택 상태 관리 (직선, 사각형, 원)
  - ComboBox를 이용한 색상 선택 기능 구현
  - TrackBar를 이용한 선 두께 조절 기능 구현
  - PictureBox를 이용한 캔버스 구성
  - Bitmap과 Graphics 객체를 이용한 그림 그리기 구조 구현
  - 마우스 이벤트(MouseDown, MouseMove, MouseUp)를 이용한 드래그 처리 기반 설계
---

## 실행 화면 (과제1)
![실행화면](img/screenshot-1.png)

- 구현한 내용 ( 위 그림 참조)
  - UI 구성: 도형선택,색선택,굵기선택,캔버스구성
  - 도형선택: 버튼 3개를 이용해서 직선,사각형,원 선택
  - 색 선택 : ComboBox를 이용해서 검은색,빨간색,파란색,초록색 선택
  - 선 굵기 선택:TrackBar 이용해서 선 굵기를 1~10단계로 선택
  - 캔버스: PictureBox를 이용해서 캔버스 구성



## 실행 화면 (과제2)
![실행화면](img/screenshot-2.png)

- 구현한 내용 ( 위 그림 참조 )
  - 도형 선택 기능 구현 : 직선,사각형,원 그림 그리기 기능 구현
  - 색 선택 기능 구현 :ComboBox를 이용해서 4가지 색상 중에서 선택하는 기능 구현
  - 선 굵기 선택 기능 구현 : TrackBar를 이용해서 1~10까지 굵기 중에서 선택하는 기능 구현
  - 마우스 드래그 : 마우스를 드래깅 할 때는 점선으로 도형 표시하는 기능 구현
  