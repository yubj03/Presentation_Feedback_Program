Presentation Feedback Program
1. 전처리
- 라벨링 데이터
  : 하나의 데이터 프레임으로 병합, 필요 없는 데이터 삭제, eval_grade를 float type 점수로 변환
- 원본 데이터
  : 라벨링 데이터와 매핑, 정상 재생 여부 확인, 오디오 파일로 변환

2. Presentation Feedback Program 구현
- 각 지표들로 grade점수 상관관계 분석(머신러닝 활용)
- 오디오에서 sst 발화 내용 추출
- sst 발화 내용 바탕으로 cnt 산출하고 바탕으로 점수(repeat, filler, pause, wrong) 분석(머신러닝 활용)
- 오디오 바탕으로 voc quality, voc speed 구하기
