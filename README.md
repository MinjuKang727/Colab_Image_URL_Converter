# Colab Image URL Converter
> 구글 코랩에서 텍스트 작성시, 이미지를 붙여넣으면 URL이 엄청나게 긴 문자열로 변환되어 너무 불편해서 만든 페이지입니다.  
> **구글 드라이브에 업로드된 이미지 공유 링크**만 변환 가능합니다.

## 웹 페이지 구성

- 웹 페이지 첫 화면
  - 페이지 이름, 소개, 사용법 설명, URL 변환 input 박스 및 버튼으로 구성
  - 입력창(input박스)에 커서 autofocus
    ![웹페이지 첫 화면](https://github.com/user-attachments/assets/2ba752de-f77f-4977-a020-9852c5468a1b)
- 구글 드라이브 공유 URL 붙여넣기 했을 때
  - URL 변환 후, 클립 보드 복사 안내창이 뜸
    ![구글 드라이브 공유 URL 붙여넣기 했을 때 웹페이지 화면](https://github.com/user-attachments/assets/5f0a2aee-a4f3-41ee-9552-a1ab9088dc0c)
  - alert창의 확인 버튼을 누른 후, 웹페이지
    - 입력창 아래에 변환된 URL 표시됨 : *혹시 클립보드에 복사되지 않은 경우를 대비하여 표시함.*
    - 입력창에 입력한 문자열 모두 삭제
    - 입력창에 커서 autofocus    
    ![유효한 URL 변환 시 alert창 확인 후, 웹페이지 화면](https://github.com/user-attachments/assets/7142c7a5-1364-498a-a83e-c2e9409853d2)
- 유효하지 않은 URL을 입력했을 때
  - 잘못된 URL을 입력했다고 알려주는 안내창이 뜸
    ![잘못된 URL을 입력했다고 알려주는 안내창이 뜬 웹페이지 화면](https://github.com/user-attachments/assets/ce684a91-567e-478c-94a9-a82ee11074e3)
  - alert창의 확인 버튼을 누른 후, 웹페이지
    - 입력창에 입력한 문자열 모두 삭제
    - 입력창에 커서 autofocus
    ![유효하지 않은 URL 변환 시 alert창 확인 후, 웹페이지 화면](https://github.com/user-attachments/assets/c12f8186-aeeb-442e-8efb-db26c9e3665e)






