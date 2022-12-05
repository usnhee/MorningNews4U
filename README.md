# MorningNews4U / 줄넘귀(줄여서 넘겨줘요 귀로)
- 내가 원하는 검색어의 뉴스를 세 줄로 요약해 읽어주는 서비스 
- 준비하면서, 이동하면서, 운동하면서 들을 수 있어 사용자의 시간을 절약해주는 서비스

# Tools / 사용한 기술 
- Naver Clova API Summary, AI Voice Word to Voice
- Postman, FastAPI

# How to use / 사용 방법 
(* demo 사이트로 프로젝트 진행했고 현재는 운영하고 있지 않습니다.) 
- 사용자가 사이트에서 검색어와 언론사를 선택합니다.
- 해당 검색어의 뉴스를 찾아 크롤링을 통해 본문을 가져와 Naver Clova API의 Summary를 활용해 세 줄로 요약합니다. 
- 요약된 내용을 Naver Clova API AI Voice로 읽어줍니다. 
