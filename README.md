# 건설빅데이터분석 · 그래프 신경망 — 실습 노트북

경희대학교 건축공학과 대학원 · PyTorch Geometric(PyG) 실습 노트북 저장소
강의 영상: e-campus(Canvas) 과목 모듈

## 실습 목록

| 실습 | 주제 | 실습본 (빈칸 채우기) | 완성본 (정답 · 실행결과) |
|:-:|---|:-:|:-:|
| PyG GNN 네 모델 · Cora | Cora 논문 인용 그래프에서 VanillaGNN·GCN·GAT·GraphSAGE를 직접 구현하고 비교 (전이·귀납) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baekja/Lecture_GNN-AE-Practice/blob/main/PyG_FourGNN_Cora/cora_gnn4_practice.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baekja/Lecture_GNN-AE-Practice/blob/main/PyG_FourGNN_Cora/cora_gnn4_complete.ipynb) |
| PyG GNN 네 모델 · 골조 | 손으로 계산할 수 있는 전단빌딩 골조 400동으로 절점 변위 예측과 층간변위 검토 (전이·귀납) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baekja/Lecture_GNN-AE-Practice/blob/main/PyG_FourGNN_Frame/frame_gnn4_practice.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baekja/Lecture_GNN-AE-Practice/blob/main/PyG_FourGNN_Frame/frame_gnn4_complete.ipynb) |
| PyG GNN 다섯 모델 · Cora·PROTEINS | Cora 노드 분류와 PROTEINS 그래프 분류에서 VanillaGNN·GCN·GAT·GraphSAGE·GIN을 비교 (표현력과 정확도, mean/sum 리드아웃) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baekja/Lecture_GNN-AE-Practice/blob/main/PyG_FiveGNN_PROTEINS/gnn5_practice.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baekja/Lecture_GNN-AE-Practice/blob/main/PyG_FiveGNN_PROTEINS/gnn5_complete.ipynb) |

## 예제 (강의노트 연계)

| 예제 | 주제 | 노트북 (설명 · 실행 결과 포함) |
|:-:|---|:-:|
| 링크 예측 · 트러스 | 직접 만든 Pratt · Howe 트러스 60동에서 가린 부재를 휴리스틱 6종 · GAE · VGAE · MLP 디코더 · SEAL 간이판으로 찾고, 복원한 트러스를 직접강성법으로 검증 (W09 링크 예측) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baekja/Lecture_GNN-AE-Practice/blob/main/PyG_LinkPred_Truss/truss_linkpred_example.ipynb) · [README](PyG_LinkPred_Truss/README.md) |

## 사용법
1. 위 표의 **Open in Colab** 배지를 누릅니다.
2. Colab 메뉴 **파일 → Drive에 사본 저장** 을 누른 뒤, 사본에서 작업합니다.
3. 위에서부터 차례대로 셀을 실행합니다(`Shift + Enter`). 첫 셀이 PyG가 없으면 설치합니다. GPU는 필요 없습니다.

## 라이선스
- 코드: [MIT](LICENSE)
- 노트북의 설명 글(마크다운): [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ko)
