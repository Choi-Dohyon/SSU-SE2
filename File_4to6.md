## 글 강조하기

</br>

1. 볼드체

    먼저, 볼드체를 사용하는 방법을 알아봅시다.

    볼드체 사용 방법에는 2가지가 있습니다.

    </br>

    첫번째는 *를 이용한 방법입니다.

        볼드체로 **강조하기**  
        
        중간**강조**하기

    </br>

    두번째는 _를 이용합니다.

        볼드체로 __강조하기__

    하지만 _의 경우에는 *와 달리 '**쓸 수 있는 상황이 한정적**'이기 때문에 주로 *를 사용합니다.

    </br></br>

2. 이탤릭체

    이탤릭체도 볼드체와 마찬가지로 *와 _를 사용합니다.

    대신 볼드체와 달리 문자를 1개씩만 사용합니다.

        이탤릭체로 *기울이기*

        중간*기울*이기

        이탤릭체로 _기울이기_

    로 사용할 수 있습니다.

    이탤릭체도 볼드체처럼 _보다는 주로 *를 사용합니다.

    </br></br>

3. 볼드체 + 이탤릭체  

    특정 부분을 강조하는 동시에 기울이고 싶다면 *나 _를 3번씩 사용하면 됩니다.

    사용 방법은 볼드체, 이탤릭체와 같습니다.

---

</br>

## 인용문

</br>

인용문은 새로운 블록을 만들어서 그 안에 내용을 적을 수 있습니다.

인용문은 > 를 사용해서 다음과 같이 사용할 수 있습니다.

    > 인용문1

그러면 아래와 같이 새로운 블럭안에 텍스트가 들어갑니다.

> 인용문1

</br>

인용문에 들어갈 문장이 여러개라면 다음과 같이 적으면 됩니다.

    > 인용문1
    > 
    > 인용문2

</br>

인용문 안에서는 Markdown의 구문들을 그대로 사용할 수 있습니다.

인용문 안에 제목을 넣을 수도 있고, 볼드체를 사용할 수도 있으며, 인용문 안에 인용문을 넣을 수도 있습니다.

인용문 안에 인용문을 넣는 방법은 다음과 같습니다.

    > 인용문1
    >
    >> 인용문2

이제 아래와 같은 인용문도 만들 수 있을 것입니다.

ex )

> ### 인용문 테스트
>
> **인용문1**
>> *인용문2*
>>
>> 인용문3  

뒤에 나오는 Markdown의 구문들 역시 인용문 안에서 사용할 수 있습니다.

---

</br>

## 리스트

</br>

목차를 적거나, 여러 항목들을 나열할 때 리스트를 사용할 수 있습니다.

리스트는 순서가 있는 리스트와 순서가 없는 리스트로 나눌 수 있습니다.

</br>

1. 순서가 있는 리스트

    순서가 있는 리스트는 다음과 같이 적는 것이 일반적입니다.

        1. 리스트1
        2. 리스트2
        3. 리스트3
        4. 리스트4

    물론, 다음과 같이 적어도 위와 같은 결과의 리스트가 생성됩니다.

        1. 리스트1
        1. 리스트2
        1. 리스트3
        1. 리스트4

    또는

        1. 리스트1
        8. 리스트2
        5. 리스트3
        6. 리스트4

    첫번째 항목의 숫자가 1이기만 한다면 뒤에 나오는 항목들의 숫자는 별로 상관없다는 뜻입니다.

    </br>

    리스트 안에 리스트나 인용문 등을 넣는 것도 가능합니다.

        1. 1번 문장
        2. 2번 문장
            > 인용문
        3. 3번 문장
            1. 3-1번 문장
            2. 3-2번 문장
        4. 4번 문장

    </br></br>

2. 순서가 없는 리스트

    순서가 없는 리스트에서는 항목 앞에 -, +, *를 붙여줍니다.

        - 리스트1
        - 리스트2
        - 리스트3

    또는

        + 리스트1
        + 리스트2
        + 리스트3
    또는

        * 리스트1
        * 리스트2
        * 리스트3

    순서가 없는 리스트도 역시 리스트 안에 Markdown의 다른 구문들을 넣을 수 있습니다.

    </br>

* **주의사항**

    순서가 없는 리스트를 만들 때는 되도록 앞에 붙이는 문자(-, +, *)를 통일하도록 합시다.

---

</br>