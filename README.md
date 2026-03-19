1. 😎다중선형회귀 모델(머신러닝과 딥러닝의 분석 차이 확인)
    - source file (ML_LinearRegression,DEEP_LinearRegression)
    - Boston housing Data 활용, google colab edit 활용, tensorflow,keras 라이브러리 활용
    - 결과 - 딥러닝모델로 구성시 성능향상이 있었다.   
  
2. 😍시계열 모델 , 💔자연어 처리 모델
    - 가상화폐 가격 분석 예측 source file
      - crypto_coinrnn.py : lstm 모델 구성 및 훈련 파일
      - web_service.py : 플라스크 웹 라우팅
      - ai_tools(D) : ai 관련 모델 및 도구
        - interface_service.py : 모델 예측 서비스 연동 인터페이스
        - crypto_coin(D) : 분석모델 및 도구
          - coin_model.py :  예측모델
          - config(D) : 로브스트 전처리 저장된 객체
      - templates(D) : html 파일
      - static (D) : 정적파일
        - apps(D) : javascript 파일
        - css(D) : css 파일
        - images(D): 페이지 서비스 이미지 파일
    
    - 스미싱 문자 메시지 위험도 및 판별 모델
        -ai_tools(D) : 
        - smithing_anal : 관련 모델 및 환경파일
            -ai_files(D) : 
                config : 단어사전 및 최대길이등의 환경 데이터
                nlp_smithing.keras : 사전 훈련된 모델
                nlp_smithing.weights.h5 : 별도로 저장된 모델의 가중치
                vectornize : TextVecternize 전처리 객체
            -sms_model.py : 훈련된 모델 임포트와 interface_service.py 와 연동하여 서비스 제공
</pre>
