# CSA_OSA_논문참여
# 논문 기여 부분
# 아주대학교 신경과 특임연구원으로 재직하며 교수님의 논문작성을 도왔으며 이때 기여한 부분은 다음과 같습니다
# 1.데이터 탐색 및 전처리 
# 2.데이터 시각화
# 3.CSA,OSA 구분 작업
# 각 기여 부분에 대한 설명은 다음과 같다

# DB사용 부분
#PPT 파일 참고(의료정보학과 데이터 접근 및 시각화)

# 데이터 탐색 및 전처리 부분
# 환자의 번호를 받고 sql를 통해 anonymous id를 찾는다.
# anonymous id를 통해 환자 심전도,호흡곡선,산소포화도 등의 데이터를 gz 파일로 추출한다.
# 각 형식에 맞는 gz 파일 압축 푸는 코드를 통해 수치 데이터를 뽑아낸다.
# 데이터를 뽑아낸후 시간별로 정리한다.

# 데이터 시각화
# 보통 30분 간격으로 데이터를 시각화 하였으며 교수님의 요청에 따라 그때그때 변화를 주었다.
# 데이터 마다 편차가 심했기 때문에 환자 일일 데이터 마다의 표준편차와 평균을 이용하여 상한선 및 하한선을 만들었다.

#CSA,OSA 구분작업
#논문에 필요한 작업으로 만들어진 그래프를 보고 교수님의 자문을 받아 평범한 신호인지 CSA,OSA인지 판독한다.

# 해당 논문 
#체인-스토크스 호흡이 신경계 중환자의 예후에 미치는 영향
#https://www.e-jsm.org/journal/view.php?doi=10.13078/jsm.200015

#해당 코드
#make_plot.ipynb
