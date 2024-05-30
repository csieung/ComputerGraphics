# ComputerGraphics

자신만 로봇 부품을 수정하기 위해서 blender를 사용하여 '로보트 태권브이'를 오마주했다.


# 로봇 제작 과정

1. Add Cone
   
   ![image](https://github.com/csieung/ComputerGraphics/assets/72512163/564c2e86-df16-4d1f-b0e1-60dd54ba26ae)
2. Poly Build + Material 조정

   ![image](https://github.com/csieung/ComputerGraphics/assets/72512163/600ef379-8fa0-4156-87a3-7f5d85f292b1)
   ![image](https://github.com/csieung/ComputerGraphics/assets/72512163/0241ab64-584c-4d67-8360-0b41a9846e45)

3. 얼굴, 몸 모양 다듬기 : 도형 삭제 + 채우기

   ![image](https://github.com/csieung/ComputerGraphics/assets/72512163/5d8c69ec-d9b2-4280-9a51-fd3d17c01bc6)

   목 주변 불필요한 부분들을 삭제한다. 삭제한 후 비어있는 면을 채워줘야 한다.
   
4. 디자인 수정

   ![image](https://github.com/csieung/ComputerGraphics/assets/72512163/123ebc56-35c3-4503-a017-046975b4d9c3)

   로봇의 얼굴을 디자인하는 과정이다. 

6. 최종/ .fbx 파일 export

   ![image](https://github.com/csieung/ComputerGraphics/assets/72512163/63ee6efd-2cea-47a6-8bed-7ae8be88d2ac)
   ![image](https://github.com/csieung/ComputerGraphics/assets/72512163/581f6bb8-ce30-4e4b-8897-930016bb3521)

   
# 로봇 달리기 동작 적용

제 1사분면 : 원근투상
제 2사분면 : 평면도
제 3사분면 : 정면도
제 4사분면 : 측면도

OpenGL 라이브러리를 사용하여 제작한 로봇의 움직임을 구현하였다.

1. 로봇 적용 모습


   ![image](https://github.com/csieung/ComputerGraphics/assets/72512163/5f874409-0d6f-4074-b689-04feae162632)

2. 달리기 동작 구현

   ![image](https://github.com/csieung/ComputerGraphics/assets/72512163/79adb879-f78b-43f7-9014-17e66a39e67d)

4. 점프 동작 구현

   ![image](https://github.com/csieung/ComputerGraphics/assets/72512163/bbf0c7b3-df90-4945-aa5c-9f7e08f19fdc)


