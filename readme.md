# es 모듈의 임포트

## 임포트 시킬 파일을 만들기

- export 키워드로 다른 파일에서 가져 갈 수 있게 넘겨줌
- default를 붙이면 import 할때 임포트한 이름으로 바로 사용 가능
- default가 없으면 { words } 이런식으로 destructuring 해서 사용 가능

## main.js에서 임포트 시키키

- import words from './words.js' 로 임포트
- 이때 html에서 main.js를 불러올때 type="module" 속성을 script 태그에 넣어줘야 import를 사용할 수 있음
- 이 외에 직접만든 모듈이 아닌 경우 webpack(모듈번들러)의 설정이 필요함
