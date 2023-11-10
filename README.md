- 23-2 파이썬활용인공지능기초 강의 코드 정리

- google maps 환경변수

  ```py
  from dotenv import load_dotenv
  import os

  load_dotenv()
  my_key = os.getenv("GOOGLE_MAP_API_KEY")
  ```
