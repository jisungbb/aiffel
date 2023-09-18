# AIFFEL Socar Campus Code Peer Review Templete

코더 : [박지성]

리뷰어 : [김영준]

---

🔑 **PRT(Peer Review Template)**

- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 주어진 문제를 해결한 후, 시각화 까지 완료되었음
        <img src="https://i.ibb.co/M89FkrY/1.jpg">

    
    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 추가로 정의한 부분에서 주석이 달려있어 어떤 의미인지 파악이 가능합니다
    - ```python
        # temp_data, item_data를 상품명을 기준으로 merge하기
      temp_data = pd.merge(temp_data, item_data, on = '상품명' )
      temp_data
      ```
        

- (X)  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 새로운 시도의 부분은 있으나, 오류에 대해 해결한 부분은 따로 없습니다.
  
        
- [O]  **4. 회고를 잘 작성했나요?**
    - 회고를 분류별로 나누어 잘 작성하였고, 중간중간 마크다운으로 추가적인 설명들로 인해 충분한 회고가 되었습니다.
    <img src="https://i.ibb.co/ZTNb5LY/2.jpg" >

- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 전처리에 필요한 코드가 간결하고 PEP8형식에 잘 맞추어서 작성이 되어있습니다.
      <img src="https://i.ibb.co/crfnM1s/3.jpg">

---