# flutter_credit_card

Flutter credit card input

## Reference

https://dribbble.com/shots/6440077-Add-a-New-Credit-Card-alternate-flow

![sample](https://user-images.githubusercontent.com/35194820/75879920-a157a080-5e5f-11ea-9763-823ad8f1a4e5.gif)


## Real output (실제 결과물)

<img src="https://user-images.githubusercontent.com/35194820/76142013-d0168680-60ac-11ea-9007-0db57373f96f.gif" width="250" >

<!-- 
![output](https://user-images.githubusercontent.com/35194820/76142013-d0168680-60ac-11ea-9007-0db57373f96f.gif) -->


## Total elapsed time (총 개발 기간)

- 4 day

## Source Tree

```
lib
├─ components
│  ├─ back_card_view.dart
│  ├─ card_cvv.dart
│  ├─ card_logo.dart
│  ├─ card_name.dart
│  ├─ card_number.dart
│  ├─ card_sign.dart
│  ├─ card_valid.dart
│  ├─ front_card_view.dart
│  ├─ input_view_pager.dart
│  ├─ my_appbar.dart
│  ├─ round_button.dart
│  └─ yellow_border.dart
├─ constanst.dart
├─ main.dart
├─ provider
│  ├─ card_cvv_provider.dart
│  ├─ card_name_provider.dart
│  ├─ card_number_provider.dart
│  ├─ card_valid_provider.dart
│  └─ state_provider.dart
├─ screens
│  └─ MainScreen.dart
└─ util
   └─ util.dart

```

## 3rd party library

### Flip card 

https://pub.dev/packages/flip_card

For use card flip animation

### Provider

https://pub.dev/packages/provider

For use state management


## Note

- 이 코드는 모든 디바이스의 해상도를 지원하지 않습니다. 특정 디바이스 에뮬레이터에서 bottom pixel overflow가 발생할수 있습니다.
- 이 코드는 모든 카드사를 체크하지 않습니다. (Visa, Master) 더 많은 카드사를 지원하기 위해서 `card_logo.dart` file을 수정하십시오

-----------------------------------------

- This code does not support the resolution of all devices. Bottom pixel overflow may occur on certain device emulators.
- This code does not check all card companies(only Visa and master). Modify the `card_logo.dart` file to support more card companies

