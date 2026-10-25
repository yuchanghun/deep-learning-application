# 딥러닝 응용 (3학년 2학기)

수업 실습 노트북, 과제1, 6장 실습, 중간고사 준비 자료를 모아 둔 저장소입니다.

| 폴더 · 파일 | 내용 |
|---|---|
| `1_2.ipynb` ~ `5_6.ipynb` | 교재 장별 실습 노트북 |
| `A_pretrained_yolo_seg.ipynb` | 과제1 프로그래밍 A: 사전 학습 YOLOv8-seg로 분할 추론 |
| `B_unet_oxford_pet.ipynb` | 과제1 프로그래밍 B: U-Net을 직접 쌓아 Oxford-IIIT Pet 분할 |
| `제출/` | 과제1 제출본 (실행 출력이 포함된 노트북, 서술 답안) |
| `6_5.ipynb` | 6장 실습: DCGAN으로 MNIST 숫자 생성 |
| `6_5_과제.ipynb` | 6장 과제 6개 실험 노트북 (아직 실행 결과 없음) |
| `중간고사_준비/` | 셀 1~5 템플릿 노트북, 실행 예시, 준비자료 PDF |

## 실행 환경

- Python 3.11, PyTorch 2.14 (CUDA 13.0), torchvision, ultralytics, matplotlib, pandas
- 데이터(MNIST, Oxford-IIIT Pet, PASCAL VOC 2012)와 YOLO 가중치는 저장소에 넣지 않았습니다. 노트북을 실행하면 `data/` 폴더에 자동으로 내려받습니다.
