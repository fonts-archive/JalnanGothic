# 여기어때 잘난체 고딕

[배포처 바로가기](https://gccompany.co.kr/font)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Jalnan Gothic`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/JalnanGothic/JalnanGothic.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/JalnanGothic/JalnanGothic.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Jalnan Gothic';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/JalnanGothic/JalnanGothic.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/JalnanGothic/JalnanGothic.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/JalnanGothic/JalnanGothic.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/JalnanGothic/JalnanGothic.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/JalnanGothic/subsets/JalnanGothic-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/JalnanGothic/subsets/JalnanGothic-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Jalnan Gothic", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
• '여기어때 잘난체'는 여기어때에서 배포하는 글꼴(잘난체·잘난체2·잘난체 고딕)이 모두 포함된 명칭으로, 
  '여기어때 잘난체'의 지적재산권은 (주)여기어때컴퍼니가 소유하고 있습니다.
• '여기어때 잘난체'는 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며 자유롭게 사용할 수 있습니다.
• '여기어때 잘난체' 글꼴 파일(otf/ttf) 자체를 유료로 판매하거나 어떠한 형태로든 임의 수정·개작하여 
  글꼴을 재배포 하는 것은 금지합니다.
• '여기어때 잘난체'는 인쇄물, 광고물(온·오프라인), 상품, CI·BI 등 상업적 목적으로 사용할 수 있습니다.
  ① 글꼴 그대로의 사용을 권장하며, 형태 변환이 필요한 경우 글꼴의 조형성을 해치지 않는 범위 내에서 간단한 변형이 가능합니다.
  ② 상품에 사용 시 여기어때 잘난체 라이선스 혹은 출처 표기를 권장합니다.
  ③ CI·BI에 사용 시 상표권 등록은 불가합니다.
• '여기어때 잘난체'는 본 저작권 안내와 라이선스 전문을 포함해서 다른 소프트웨어에 임베딩 또는 번들하여 
  판매하거나 재배포가 가능합니다.
  임베딩 된 폰트는 별도 판매 불가합니다.
• '여기어때 잘난체' 사용 시 라이선스 전문을 포함하기 어려울 경우 '여기어때 잘난체'의 출처 표기를 권장합니다.
  예) 이 상품에는 (주)여기어때컴퍼니가 제공한 여기어때 잘난체·잘난체 고딕이 적용되어 있습니다.
• '여기어때 잘난체'를 사용한 인쇄물, 광고물(온·오프라인), 상품, CI·BI 등의 이미지는 여기어때의 
  마케팅을 위해 활용될 수 있습니다. 이를 원치 않는 사용자는 언제든지 당사에 요청하실 수 있습니다.
```
