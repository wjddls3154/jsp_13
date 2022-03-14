# jsp_13 : 반복문 (for 문, while 문)

![image](https://user-images.githubusercontent.com/37132897/158113610-e9f911a9-8e42-4d75-a963-7b65c066c483.png)
- for 문 : 10,20,30,40,50 반복문 출력
- while 문 : 0부터 9까지 반복문 출력

      // for 문 사용
      
      array = [10, 20, 30, 40, 50];
      
      for (var i = 0; i < array.length; i++) { // 인덱스 0부터, 배열의 길이 미만까지 출력
      
        document.write(array[i]);
        
        document.write("<br>");
        
      }
      
      // while 문 사용
      
      j = 0;
      
      while (j < 10) { // j가 0이므로, 0부터 10 미만의 숫자까지 출력
     
        document.write(j);
        
        document.write("<br>");
        
        j++;
        
      }
