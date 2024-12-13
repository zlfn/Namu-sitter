# Namu-sitter
[나무마크](https://namu.wiki/w/%EB%82%98%EB%AC%B4%EC%9C%84%ED%82%A4:%EB%AC%B8%EB%B2%95%20%EB%8F%84%EC%9B%80%EB%A7%90)를 위한 증분 파서

## 문제
* 공개되어있는 오픈소스 나무마크 파서는 느리거나 불안정함
* 증분적으로 파싱할 수 없어서 문서 일부가 변경되어도 전체를 다시 렌더링해야함
* 프론트엔드에서 사용할 수 있는 JS/WASM 구현이 없음

## 목표
* [Tree-sitter](https://tree-sitter.github.io/)를 이용한 나무마크 증분 파서 및 WASM 바인딩 제공
* 증분 파서를 이용한 WASM 렌더러 개발
* 문서에 Live Preview를 제공할 수 있을 정도로 충분히 빠를 것
* [오픈나무](https://github.com/openNAMU/openNAMU)에 기여 혹은 새로운 위키 엔진 개발

## 지원 (예정) 스펙
* 모든 [나무마크 문법](https://namu.wiki/w/%EB%82%98%EB%AC%B4%EC%9C%84%ED%82%A4:%EB%AC%B8%EB%B2%95%20%EB%8F%84%EC%9B%80%EB%A7%90)
* [오픈나무마크 문법](https://2du.pythonanywhere.com/w/%EC%83%88%EB%A1%9C%EC%9A%B4%3A%EB%A0%8C%EB%8D%94%EB%9F%AC%2F%EC%98%A4%ED%94%88%EB%82%98%EB%AC%B4%EB%A7%88%ED%81%AC)
