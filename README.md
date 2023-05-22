# programmers
## 코딩 테스트
#### ad 제거하기
    def solution(strArr):
      answer = []
      for i in strArr:
          if "ad" not in i:
            answer.append(i)
      return answer
      
#### l로 만들기
    def solution(myString):
    letter = ["a", "b", "c", "d", "e", "f", "g", "h", "i", "j", "k"]
    
    for i in letter:
        myString = myString.replace(i,"l")
    return myString
    
#### 특정문자 대문자로 만들기
    def solution(my_string, alp):
    answer = []
    for i in my_string:
        if i == alp:
            i = i.upper()
            answer.append(i)
        else:
            answer.append(i)
    a = ''.join(answer)
    
    return a

#### rny_string
    def solution(rny_string):
    answer = ''
    for i in rny_string:
        if 'm' in rny_string:
            answer = rny_string.replace('m', 'rn')
        else:
            answer = rny_string
            
    return answer
