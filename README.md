# OpenMind

## CheckList
- [x] 1. [공통] 제시된 폰트, 컬러 시스템을 설정하고 재사용성을 위해 공용 컴포넌트를 만들어 주세요, 반응형 웹 디자인을 준수해 주세요.


- [x] 2. [메인 페이지] 이름을 입력하고 '질문 받기' 버튼을 클릭하면 피드 생성 요청으로 피드를 생성합니다, 피드 생성 응답을 받으면 응답으로 받은 피드 id를 활용해 '/post/{id}/answer' 페이지로 이동합니다.


- [x] 3. [질문 목록 페이지] 오픈마인드 로고를 클릭하면 '/' 페이지로 이동합니다, 현재 페이지, 정렬 순서를 설정해서 카드 리스트 조회 요청합니다.(기본 정렬 순서는 '최신순'), '답변하러 가기' 버튼을 클릭 시, 질문 받기로 생성한 id가 로컬 스토리지에 없으면 메인 페이지 '/'로 이동하고, 있으면 '/post/{id}/answer' 페이지로 이동합니다,


- [x] 4. [질문 목록 페이지] PC에서 너비가 1200px 보다 커질 경우 내부 내용의 위치는 고정하고 좌우 여백만 커집니다, 카드 컴포넌트의 너비는 220px 입니다.


- [x] 5. [질문 목록 페이지] Tablet에서 상단 네비게이션 영역의 좌우 여백은 50px을 유지합니다, 카드 리스트 영역의 좌우 최소 여백은 32px 입니다, 카드 컴포넌트의 최소 너비는 186px 입니다, 카드 리스트 영역이 줄어드는 것에 따라 카드 크기가 작아지다가 186px보다 작아질 때 하나의 행에 4개 → 3개씩 보이도록 합니다.


- [x] 6. [질문 목록 페이지] Mobile에서 '누구에게 질문할까요?'는 좌측 여백 24px과 정렬 드롭 다운은 우측 여백 24px을 유지하며 둘 사이의 간격이 멀어집니다, 카드 리스트 영역의 좌우 최소 여백은 24px 입니다.


- [x] 7. [개별 피드] 답변이 완료된 질문은 '답변완료'로 표시하고 '수정하기'와 '삭제하기' 버튼이 생깁니다, 답변이 완료되지 않은 질문은 '미답변'으로 표시해주세요, 답변거절 버튼을 누르면 ‘답변거절’로 입력이 됩니다, 질문이 없는 경우 'No_question 화면'이 보입니다, '질문 작성하기' 버튼을 클릭하면 '질문을 작성하세요' 모달이 뜹니다.


- [x] 8. [개별 피드] 질문은 '최신순'으로 무한 스크롤 방식으로 배치합니다, '…'을 누르면 삭제하기 버튼이 나타나고 누르면 해당 질문이 삭제됩니다, '링크 아이콘'을 클릭하면 URL을 클립보드에 복사하고, 'URL이 복사되었습니다' 토스트가 5초 동안 보이다가 사라집니다, '카카오 아이콘'을 클릭하면 카카오톡으로 공유하는 화면이 보입니다, '페이스북 아이콘'을 클릭하면 페이스북으로 공유하는 화면이 보입니다, 좋아요, 싫어요 개수를 표시합니다.


- [x] 9. [개별 피드에 대한 질문하기 모달창] 모달의 'X' 버튼이나 모달 내용을 벗어난 부분을 클릭하면 모달을 닫습니다, 모달에 질문 내용이 없는 경우 '질문 보내기' 버튼은 비활성화 상태입니다. 질문 내용이 있는 경우 활성화 됩니다.


- [x] 10. [답변하기] 답변이 입력되면 '답변 완료' 버튼이 활성화가 됩니다, 답변이 완료된 질문에 '수정하기' 버튼을 누르면 해당 질문칸은 수정이 가능한 질문칸으로 변경이 됩니다, 수정할 내용이 없으면 '수정완료' 버튼은 활성화 되지 않습니다, 화면 최상단의 '삭제하기' 버튼을 누르면 받은 질문들과 피드가 한 번에 삭제가 됩니다.
