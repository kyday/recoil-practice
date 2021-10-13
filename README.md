# React recoil

## atom

Atom은 상태(state)의 단위
atom이 업데이트 되면, 해당 atom을 구독하고 있던 모든 컴포넌트들의 state가 새로운 값으로 리렌더됨.

## selector

Recoil에서 함수나 파생된 상태
원래의 state를 단순하게 가져오는 것이 아닌, get 프로퍼티를 통해 state를 가공하여 반환
