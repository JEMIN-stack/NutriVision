# NutriVision

NutriVision은 YOLO 기반 음식 인식과 영양 정보 기록 기능을 구현한 AI 비전 프로젝트입니다.

## 프로젝트 개요

이미지 또는 영상에서 음식을 탐지하고, 탐지된 음식 정보를 기반으로 영양 정보를 확인할 수 있도록 구성했습니다.  
Flask 기반 웹 화면과 HTML template을 활용하여 로그인, 이미지 업로드, 탐지 결과 확인, 식단 기록 화면을 구현했습니다.

## 주요 기능

- 음식 이미지 업로드
- YOLO 모델 기반 음식 객체 탐지
- Bounding Box 결과 표시
- 음식 영양 정보 CSV 연동
- 식단 기록 및 캘린더 화면 구성

## 파일 구조

```text
NutriVision/
├─ templates/
│  ├─ adjust_quantity.html
│  ├─ journal_calendar.html
│  ├─ journal_entry.html
│  ├─ login.html
│  ├─ register.html
│  ├─ result_with_bbox.html
│  ├─ upload.html
│  └─ video.html
├─ best_1003.pt
├─ Nutrivision_food_info.csv
└─ Nutrivision_food_test_H.py
```

## 사용 기술

- Python
- YOLOv8s
- HTML/CSS
- Flask
- CSV 기반 음식 영양 정보 관리


## 담당 및 구현 내용

- YOLO 모델을 활용한 음식 탐지 흐름 구성
- 음식 탐지 결과를 웹 화면에 표시
- 음식 영양 정보 CSV 연동
- 업로드, 결과 확인, 식단 기록 관련 HTML template 구성
