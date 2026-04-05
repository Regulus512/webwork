# 2026-04-05
- web1-03-12: <b>box-sizing</b>

**margin + position은 어떻게 적용되나?**

- margin test

    ```
    position으로 위치를 잡은 다음,
    margin이 적용된 위치에 box가 렌더링된다
    최종 렌더링되는 위치 = position + margin

    position: sticky의 경우
    평소에는 margin이 적용되다가
    지정한 값 이하로 요소가 스크롤되었을 때 canvas에 붙어서 지정했던
    "left, right 만큼만 띄우게된다"
    
    최종 렌더링되는 위치 = position을 우선으로 함
    DevTools의 margin 주황색 영역으로 확인 가능
    left or top-margin이 줄어들 수도 있다 (주황색 영역이 감소)
    ```

# 예제 자료 보관

### 1-03
index|title|sub-title|date|
:--:|:--:|:--:|:--
(12)|box-sizing|<span style="color:skyblue">margin+position</span>|2026-04-05
(11)|z-index(4)||2026-04-01
(11)|z-index(2,3)||2026-03-31
(11)|z-index(1)||2026-03-22
(11)|z-index||2026-03-22
(10)|Position(7,8)||2026-03-19
(10)|Propagation||"
(10)|Position(4,5,6)||2026-03-13
(10)|Position(1,2,3)||2026-03-08
(10)|Position(1)||2026-02-24
(09)|Float(1,2)||2026-02-21
(08)|vanilla css(1,2)||"
(07)|scss 2||2026-02-13
(06)|scss 1||2026-02-10
(05)|scss&sass intro||2026-01-24