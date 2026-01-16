03-2 while 문
==================
* 문장을 반복해서 수행해야 할 경우 사용함.

##### while 문의 기본 구조
* 조건문이 참인 동안 while 문의 문장들이 반복해서 수행됨.
<pre>
<code>
  while 조건문:
      수행할_문장 1
      수행할_문장 2
      수행할_문장 3
</code>
</pre>

##### while 문 강제로 빠져나가기
* break 문
<pre>
<code>
  coffee = 10
  money = 300
  while money:
      print("돈을 받았으니 커피를 줍니다.")
      coffee = coffee - 1
      print("남은 커피의 양은 %d개입니다." % coffee)
      if coffee == 0:
          print("커피가 다 떨어졌습니다. 판매를 중지합니다.")
          break
</code>
</pre>

##### while 문의 맨 처음으로 돌아가기
* continue 문
<pre>
<code>
  a = 0
  while a < 10:
        a = a + 1
        if a % 2 == 0: continue
        print(a)
</code>
</pre>

##### 무한 푸르
<pre>
<code>
  while True:
      수행할_문장1
      수행할_문장2
</code>
</pre>
