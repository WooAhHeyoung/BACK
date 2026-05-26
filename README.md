  ## Front랑 합쳐야 해요~!!!!

  ### 실행
  1. 환경변수 설정

  ```bash
  cp backend/.env_example backend/.env
  # backend/.env 열어서 UPSTAGE_API_KEY에 실제 키 입력

  2. Python 패키지 설치

  cd backend
  python -m venv .venv
  .venv/bin/pip install -r requirements.txt
  cd ..

  3. npm 패키지 설치 (프론트엔드 포함)

  npm install
  npm --prefix jeonse-risk-checker-main install

  4. 실행

  npm run dev        # fake 모드 (API 키 없이 테스트)
  npm run dev:real   # 실제 Upstage API 호출
