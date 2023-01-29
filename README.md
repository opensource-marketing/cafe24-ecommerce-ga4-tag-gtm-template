# 카페24 GA4 전자상거래 GTM 태그 템플릿

## 작성자

오픈소스마케팅(https://osoma.kr)

## Release notes

| Date       | Notes                                                                          |
| ---------- | ------------------------------------------------------------------------------ |
| 2023.01.29 | GA4 전자상거래 이벤트에 필요한 items, transaction_id, value, shipping 매개변수 |

## 설명

카페24 쇼핑몰을 위한 GA4 전자상거래 관련 이벤트를 손쉽게 추가할 수 있는 태그 템플릿입니다.

아래 이벤트별 지원 매개변수를 참고하세요.

### view_item, add_to_cart, view_cart, begin_checkout 이벤트

- items 매개변수 지원(item_id, item_name, price, quantity)

### purchase 이벤트

- items 매개변수 지원(item_id, item_name, price, quantity)
- transaction_id, value, shipping 매개변수 지원
