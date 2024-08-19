# Javascript Plugin
## 공통 주의사항
* 각 플러그인 사용 시 해당 플러그인의 필수 연결 파일 먼저 확인하기!!
* css,js 파일 확장자가 서로 다른 경우 있으니 이름과 함께 확장자 반드시 확인!!
## Swiper
* swiper, swiper-wrapper, swiper-slide
* 위 3개의 클래스명은 swiper 적용의 기본명칭이므로 반드시 수정없이 그대로 작성하기!
* 위 공통 명칭 외에 각 swiper 구분용으로 `div class="swiper"` 시작태그에 한칸 띄고 별도의 구분용 클래스 적용하기 ex) `div class="swiper main_slide"`
* swiper 플러그인 적용 대상에 nth 관련 수열선택자 사용하지 않기!
* `swwoper-slide`를 개별로 구분하고 싶다면? nth 수열선택자 사용하지 않고 개별 클래스 적용해서 디자인 또는 동적 결과 사용하기 예)`div class="swiper-slide slide1"
* swiper 적용 대상에 원하는 태그 추가는 swiper-slide 안에서만 사용하기(태그제한없음) 
### Swiper css 주의사항
* swiper, swiper-wrapper, swiper-slide
* 위 기본 클래스명 기준 swiper, swiper-wrapper 기본 css가 내장되어있기 때문에 반드시
그 점을 체크하고 원하는 css를 설정해야 한다.
*공통 swiper 클래스 대상 기준 사용 가능한 css list : `width, margin, padding, position,transform, 꾸미는 속성(background,color,font...)
* 공통 swiper, swiper-wrappe 클래스에 flex 설정금지!
* 공통 swiper, swiper-wrappe  금지속성: 레이아웃 관련한 속성들(position, flex, float, width
, height,margin(padding만 가능))