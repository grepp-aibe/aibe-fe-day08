# git clone https://github.com/qus0in/push_me_01_01 tdd_answer_01 # 강사 풀이

# https://github.com/grepp-aibe/push_me_01_01 # 이걸 포크

git clone https://github.com/{본인_소유}/push_me_01_01 tdd_01 # 이름 바꿔도 되고 안바꿔도 됨
cd tdd_01/
npm install # mac일 경우 sudo npm install 후 암호 입력해야할 수도
npm test # 전체
npm test problem01/problem01.test.js # 부분 실행 (숫자를 수정)

git add .
git commit -m "fix"
git push -u origin main

# github actions 작동함

# 만약에 다 통과한다면... pull request를 요청해본다

# 그러면 원본에 actions가 돈다 -> 성공하면 그 링크를 제출한다 -> 제출 양식과 성공 조건은 LMS 참고
