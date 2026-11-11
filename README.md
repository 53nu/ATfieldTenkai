# ATfieldTenkai — AT-Field

[한국어](README.md) · [English](README.en.md)

**손바닥을 펼치는 동작에 반응해 AT 필드와 그래픽 인터페이스가 전개되는 인터랙티브 비주얼 작업이다.**

[Notion 프로젝트 소개](https://53nu.notion.site/AT-Field-MediaPipe-TouchDesigner-415b42633c8c8174ae5efd57dba98865) · [작품 영상](https://www.instagram.com/1015_53nu/reel/DVXcv0QjyT-/) · [프로젝트 다운로드](https://github.com/53nu/ATfieldTenkai/releases)

## 프로젝트 소개

에반게리온의 AT 필드를 모티프로 MediaPipe와 TouchDesigner를 연결한다. MediaPipe의 Gesture Recognition으로 열린 손바닥을 인식하고, 해당 동작에 맞춰 AT 필드와 타이포그래피, 스펙트럼 비주얼, GUI를 함께 작동시킨다.

## 구현과 시각 구성

- **입력과 반응:** 카메라에서 인식한 손동작을 시각 효과의 실행 조건으로 사용한다.
- **GUI 표현:** Noise TOP, Feedback TOP과 Palette의 Graph 컴포넌트 등을 활용해 화면 요소를 구성한다.
- **타이포그래피:** 명조 계열의 글자와 Helvetica를 조합해 원작에서 인상 깊었던 그래픽 요소를 표현한다.
- **화면 구성:** 카메라 영상, AT 필드와 그래픽 패널을 하나의 장면에 배치한다.

노션에서 제작 설명과 영상 미리보기를 함께 확인한다.

## 기술

TouchDesigner · MediaPipe Gesture Recognition · Noise TOP · Feedback TOP · Graph

## 다운로드와 실행

이 저장소는 프로젝트 소개를 제공하고 배포 파일은 [Releases](https://github.com/53nu/ATfieldTenkai/releases)에서 관리한다.

1. [배포 페이지](https://github.com/53nu/ATfieldTenkai/releases/tag/v1.0)에서 `ATfieldtenkai.zip`을 내려받아 압축을 해제한다.
2. 포함된 TouchDesigner 프로젝트 파일을 연다.
3. 카메라 입력과 MediaPipe 연결을 확인한 뒤 손바닥을 펼쳐 반응을 확인한다.

실행에는 TouchDesigner와 카메라 입력 환경을 사용한다. 세부 실행 환경과 외부 파일 경로는 배포 프로젝트에 맞춰 확인한다.

## 작업 성격과 연락처

에반게리온에서 영감을 받은 비공식 팬 작업이며 예술적 실험을 목적으로 제작한다. 작품에 관한 문의는 [Instagram @1015_53nu](https://www.instagram.com/1015_53nu/)의 DM으로 받는다.
