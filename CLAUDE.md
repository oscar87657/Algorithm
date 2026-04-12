# CLAUDE.md

이 파일은 이 디렉토리에서 작업하는 Claude Code(claude.ai/code)에게 안내를 제공합니다.

---

## 디렉토리 목적

이 디렉토리는 **알고리즘 중간고사 오픈북 대비 자료**를 보관합니다.

- 대상 강의: Korea University Sejong, DCSS309-00 알고리즘 (Spring 2026)
- 교재: CLRS *Introduction to Algorithms, 3rd Edition*
- 시험 범위: W01~W06

---

## 파일 구성

| 파일 | 설명 |
|------|------|
| `중간고사_알고리즘_완전정복.md` | W01~W06 전 범위 오픈북 정리 노트 (한국어) |

---

## 정리 노트 구조 (`중간고사_알고리즘_완전정복.md`)

| 섹션 | 내용 |
|------|------|
| W01 | 알고리즘 정의·속성, 고전 문제 (최댓값, 이진탐색, GCD, 거스름돈, 오일러 경로) |
| W02 | 시간 복잡도, 점근적 표기법 (Big-O/Ω/Θ), 점화식 3가지 풀이법, 마스터 정리 |
| W03 | 연결 리스트·스택·큐·힙, 정렬 알고리즘 전체 비교 (O(n²) ~ O(n)) |
| W04 | 분할 정복 패러다임, 병합 정렬, 퀵 정렬·PARTITION, 선택 문제, 최근접 쌍 |
| W05 | 그리디 알고리즘 전체: 분할 배낭, 활동 선택, 작업 스케줄링, 허프만, MST(크루스칼·프림), 다익스트라 |
| W06 | 동적 프로그래밍: 메모이제이션 vs 타뷸레이션, LCS, 0-1 배낭, 플로이드-워셜, 편집 거리 |
| 비교 요약 | 알고리즘 패러다임 비교표, 정렬 총정리 표, 마스터 정리 케이스 예시 |

---

## 자료 수정 시 주의사항

- **원본 강의 자료 위치**: `C:\Users\송인석\Desktop\temp_source\` (W01~W06 디렉토리)
- 원본 자료는 영문(`.md`)과 한글(`.ko.md`) 양방향으로 작성되어 있음
- 정리 노트를 수정할 때는 원본 `temp_source` 강의 자료를 먼저 확인하고 반영할 것

---

## GitHub 연동

이 디렉토리의 정리 노트는 아래 저장소에 푸시되어 있습니다.

- **저장소**: `https://github.com/oscar87657/Algorithm.git`
- **브랜치**: `main`
- **로컬 클론 경로**: `C:\Users\송인석\Desktop\Algorithm_GitHub\`

정리 노트를 수정한 뒤 GitHub에 반영하려면:

```bash
cp "C:/Users/송인석/Desktop/Algorithm_Midterm_Study/중간고사_알고리즘_완전정복.md" \
   "C:/Users/송인석/Desktop/Algorithm_GitHub/"
cd "C:/Users/송인석/Desktop/Algorithm_GitHub"
git add 중간고사_알고리즘_완전정복.md
git commit -m "Update midterm study guide"
git push origin main
```
