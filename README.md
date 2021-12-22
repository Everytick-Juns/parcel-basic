# json package
## parcel-plugin-static-files-copy
- 해당 패키지는 build 과정에서 따라오지 못하는 이미지 명을 그대로 옮겨주는 역할을 한다. (favicon)
- json 추가: staticFiles
## postcss, autoprefixer
- 해당 패키지는 이전 버전의 웹 브라우저를 지원하고 관리하기 위해 사용한다.
- json 추가 : browserlist
- 파일 추가 : .postcssrc.js 여기서 .은 숨김을 의미한다.

## Babel
- ECMA2015+ 이전 버전에서 동작하기 위해 이전 버전 호환성있게 컴파일 해준다.
- install : npm i -D @babel/core @babel/preset-env
- setting : .babelrc.js / package.json - browserslist

## Babel-plugin
- install : npm i -D @babel/plugin-transform-runtime
- .babelrc.js에 plugins: ['@babel/plugin-transform-runtime'] 추가


## parcel

- 파일시스템 캐시 비활성화: 기본값, 캐시 활성
- HMR (Hot Module Replacement) 기본 활성화.
- 관련 사이트 참고.

