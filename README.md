# docker-compose-example
도커 컴포즈 연습 프로젝트


# YAML 포맷이란
YAML Ain't Markup Language의 약자입니다.  
YAML, JSON, XML 모두 사람의 가독성을 염두에 두고 설계된 포맷이지만   
YAML이 좀더 가독성에 포커싱이 많이 되어있습니다.  

## YAML 용어 및 기본 구조
- 스칼라(scalar) : 스트링 또는 숫자
- 시퀀스(sequence) : 배열 또는 리스트
- 맵핑(mapping) : 해시 또는 딕셔너리, 키/값 형태
- 맵핑 시 키/값은 `:` 을 이용해서 구분합니다 ex> key: value  
- 각 블록은 들여쓰기를 통해 구분합니다.
- 시퀀스는 들여쓰기와 `-`를 통해 표현
- `#`으로 시작하면 주석
- 하나의 스트림으로 여러개의 문서를 표현할때는 하이픈 세개(---)로 나눕니다.
- 마침표 세개(...)는 스트림의 끝을 나타냅니다.  
- 반복되는 값은 `&`를 통해 alias를 설정할 수 있습니다.
