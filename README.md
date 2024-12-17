# BOWFUN
자바와 메이븐 기반 펫 멀티샵 웹 프로그램 프로젝트에서 전반적인 기능을 모두 참여하여 제작하였습니다.
주 파트는 회원가입, 로그인, 정보 수정 및 삭제 등 관리, 결제시스템, 상품 등록 및 수정, 삭제를 담당하였습니다.

# 회원가입
![image](https://github.com/user-attachments/assets/ecc7c75e-cbd8-4cc5-a885-f3e4b26b852a)
![image](https://github.com/user-attachments/assets/f9871db1-489a-41a1-9916-0851d14ccca4)
![image](https://github.com/user-attachments/assets/6b9eb94a-30a7-4346-866e-d6c886307888)
* 인증번호 일치 확인 후, 개인정보 및 kakao api를 활용하여 주소지를 찾아 입력받을 수 있도록 제작
* 아이디와 이메일 같은 경우는 중복 확인 진행

# 로그인
![image](https://github.com/user-attachments/assets/4c3daf6f-acb7-4620-94ea-869ead97fdb5)
![image](https://github.com/user-attachments/assets/05c9ed2e-be22-4dd8-abf6-321e0a9bd79a)
* 로그인 화면으로, 둘 중 하나라도 오류가 발생하면 두 정보 중 틀린 값이 있다는 메시지가 출력되며 로그인 페이지로 리턴 설정

# 회원관리
![image](https://github.com/user-attachments/assets/2f7899e9-217b-48de-9dd8-aaefc07cb07c)
* 회원검색 및 확인을 위한 페이지. 임의로 수정 불가능
* admin이 admin 계정을 삭제하는 것 방지하기 위한 코드 작성

# 마이페이지
![image](https://github.com/user-attachments/assets/aec0aacb-54dd-4954-8719-90abf0bc02ce)
![image](https://github.com/user-attachments/assets/2fdb1426-8652-41f2-bda8-3955a1e6552d)
![image](https://github.com/user-attachments/assets/ddb285f3-b360-406e-8fc5-a5039c3a5e1f)
![image](https://github.com/user-attachments/assets/e5ac50ab-f795-4171-a18b-a39367c5c8fd)
* 내 정보를 확인하기 위한 암호 확인 후, 수정 및 삭제 가능

# 판매 상품 등록/수정/삭제
![image](https://github.com/user-attachments/assets/c30d53a8-6109-491f-b6bc-f6b39ce8c6a2)
![image](https://github.com/user-attachments/assets/7711abab-ffba-4790-8247-1c2bbc449f75)
![image](https://github.com/user-attachments/assets/b54b6be2-07b1-4647-ba17-783b3488be82)
* 상품 등록을 하는 페이지로, 업로드한 이미지를 폴더 생성 및 저장

![image](https://github.com/user-attachments/assets/fb937194-bdb1-49b0-9f12-2070cd6decb6)
![image](https://github.com/user-attachments/assets/5aec7280-863d-41b5-b11c-07c15ff26c11)
* 상품 수정을 하는 페이지로, 폴더에 저장된 교체되어 미사용하는 이미지를 삭제하는 코드 작성

![image](https://github.com/user-attachments/assets/3d55ef2a-bdb5-462c-95e8-9ca8c9473629)
* 관리자가 실수로 상품을 삭제하는 것을 방지하기 위해 알림창으로 1회 추가 확인

# 결제 서비스
![image](https://github.com/user-attachments/assets/5803ebc3-41fa-40fb-9bac-16ca29db54c9)
![image](https://github.com/user-attachments/assets/71244217-2fcb-4b9b-b89a-b765b2d9a1a4)
* 결제수단 선택 후 결제가 완료되면, 로그인 된 회원의 개인정보를 불러와 구매자와 이메일 값을 전달 받도록 설정

![image](https://github.com/user-attachments/assets/212dd4e3-24d8-43ae-a0b5-98f40d839726)
* 결제 완료 시, 구매 완료 메시지 페이지로 리다이렉트 설정

![image](https://github.com/user-attachments/assets/96234e88-8208-4781-9574-78165e4320e4)
* 결제 실패 시, 알림창 출력
