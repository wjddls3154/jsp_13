# jsp_13 : 반복문 (for 문, while 문)

![image](https://user-images.githubusercontent.com/37132897/158113610-e9f911a9-8e42-4d75-a963-7b65c066c483.png)
- for 문 : 10,20,30,40,50 반복문 출력, while 문 : 0부터10

      // for 문 사용
      
      array = [10, 20, 30, 40, 50];
      
      for (var i = 0; i < array.length; i++) {
      
        document.write(array[i]);
        
        document.write("<br>");
        
      }
      
      // while 문 사용
      
      j = 0;
      
      while (j < 10) {
     
        document.write(j);
        
        document.write("<br>");
        
        j++;
        
      }
