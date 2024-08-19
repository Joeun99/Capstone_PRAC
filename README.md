# PRAC


# 🖊️프로젝트 소개
객체 인식을 활용한 상품 자동 인식 계산대 입니다.


<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"><img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"><img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"><img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"><img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"><img src="https://img.shields.io/badge/flask-000000?style=for-the-badge&logo=flask&logoColor=white"><img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"><img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"><img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">

# 🧑맴버구성
- 장조은 : 팀장, 백엔드, 인공지능
- 성현우 : 데이터, 백엔드
- 이수현 : 디자인, 프론트
<br><br>
# ⏰개발 기간
- 23-09-03~23-12-20
<br><br>
# 💻개발 환경
- 개발환경 :  window 10
- 개발언어 : javascript, python
- 개발 툴 : visual studio code, colab
- 라이브러리 : react, flask, opencv
- 인공지능 모델 : yolov5
- 데이터베이스 툴 : mysql 8.0
- 협업 툴 : git, github
<br><br>
# 🖥 개발 내용
### Yolov5를 활용한 객체 인식

10 종류의 과자, 10 종류의 음료를 대상으로 Yolov5로 학습하였습니다.

처음에는 AI Hub의 상품 데이터를 활용했지만, 상품 인식 기능이 좋지 않아 

각 상품별로 120장씩 총 2400장을 직접  촬영 및 전처리 작업을 하여 

각 상품별로 학습 100장 검증 20장씩 사용하였습니다.

이미지 크기를 줄이기 위해 resize 작업을 하였고, Yolov5의 x, s, n, m, L 모델 각각 하이퍼 파라미터 값을 수정하며 여러 번 학습 시켰습니다.

![Untitled (1)](https://github.com/user-attachments/assets/f787b3de-7b44-4953-9d6c-3d80b1b22544)
<br><br><br><br>
그 중 n모델, Batch Size: 16, Eopch: 200 을 적용한 모델의 F1-Score가 가장 높아 해당 모델을 최종 모델로 선정하였습니다.<br><br>
![Untitled (2)](https://github.com/user-attachments/assets/db286601-d7a9-45d4-91e3-f7ad8631dc90)
![Untitled (3)](https://github.com/user-attachments/assets/f707013b-763d-4920-85a8-a459b506a82b)


<br><br><br><br>
# ▶️ 시연 영상
https://github.com/user-attachments/assets/37655875-263e-4994-ac77-8d7c1b3f7e53

<br><br><br><br>


# 📊UML 다이어그램
![image](https://github.com/dltngus02/capstone/assets/120762921/b1ea9450-cf9a-4297-9dd0-9efe91838aa0)
![image](https://github.com/dltngus02/capstone/assets/120762921/5e136e6e-b2e5-4e09-ad22-d191ca044521)
![image](https://github.com/dltngus02/capstone/assets/120762921/dec174f0-3b48-4a8a-bc18-7246b86967f5)
<br><br>
# 📊 전체 시스템 설계도
![Untitled](https://github.com/user-attachments/assets/576bbac7-46ae-4887-81aa-a24a41a7f859)
<br><br>

# 화면 구성<br><br>
![image](https://github.com/dltngus02/capstone/assets/120762921/4673a384-6e16-45bc-9f3e-ced835fe6649)<br>
메인 페이지<br><br>

<br><br><br>
![image](https://github.com/dltngus02/capstone/assets/120762921/c102bcf7-c48c-483a-955e-08698179b07e)<br>
로그인 페이지<br><br>

<br><br><br>
![image](https://github.com/dltngus02/capstone/assets/120762921/e8a73672-615b-4b3a-8f23-51266f80237b)<br>
재고 페이지<br><br>

<br><br><br>
![image](https://github.com/dltngus02/capstone/assets/120762921/4aa39a50-7017-493f-a3d7-e8f67ec37314)<br>
장바구니 페이지<br><br>

<br><br><br>
![image](https://github.com/dltngus02/capstone/assets/120762921/0c84b0df-2e07-462d-8058-2bfa6e168406)<br>
결제 페이지<br><br>

<br><br><br>
![image](https://github.com/dltngus02/capstone/assets/120762921/81b82dd4-9726-4877-a844-cc3a5e1cc6a0)<br>
결제 완료 페이지
