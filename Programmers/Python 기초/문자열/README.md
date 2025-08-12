## 접두사, 접미사 찾기  

- startswith  
  - 특정 문자로 시작하는지 확인하는 함수  
  - 리턴 값은 true 혹은 false  
  ```py
  str = 'final exam'
  
  result = str.startswith('final')
  print(result) #True
  ```

- endswith  
  ```py
  str = 'final exam'
  
  result = str.endswith('exam')
  print(result) #True
  ```  

## 공백으로 구분하기
- .split()
  ```py
  my_string = "i love you"
  result = my_string.split()
  # result = ["i", "love", "you"]
  ```  

## 영어 숫자로 바꾸기
- ord()
  ```py
  ord('a')
  # 97
  ```  
