# study_puppeteer
headless chrome library test 

### 기능조사 (필요한 기능만 정리, API사이트 정리 잘되어있음) 

#### Error발생 감지 가능
- pagerror Event

#### Console 감지 가능
- console Event

#### Screenshot
- Full Page Screenshot도 가능

#### PDF
- 하나의 페이지에 대해서는 가능, 여러개로 묶을 수 있는지 별도 사용자 Text가 들어갈 수 있는지 확인 필요

#### Request 감지 및 Intercept가능
- request Event
- page.setRequestInterception(true)로 가로챈 후 제어 가능

#### Response 감지 가능
- response Event
- response.json(), response.test() 등을 이용하여 결과값 받을 수 있음

#### Mouse, Keyboard 이벤트
- page.click(target)
- page.keyboard.down('Enter') 
- page.type('input[name=pw]', 'pw')

#### Alert, Confirm, Dialog
- dialog Event
- Custom Modal이 Native의 Alert, Confirm, Dialog와 동일하게 인식될 수 있는지 확인 필요
