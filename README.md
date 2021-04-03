# jinsta IOS \$ Android App

Screens:

- [ ] Home
- [ ] Search
- [ ] Upload
- [ ] Notifications
- [ ] Profile
- [ ] Edit Profile
- [ ] Photo Detail
- [ ] Photo Comments
- [ ] Photo Likes

1. expo init jinsta-app
   expo project를 위한 package.json 생성

2. git add .
   git이 현재 폴더안(기본)의 모든내용물(.)을 선택한다.

   git commit -m "initial commit"
   git이 현재 선택한 내용물에게 "initial commit"이란 이름을 붙혀서 저장한다.

   git remote add origin https://github.com/kimwlsgh97/jinsta-app
   git이 커밋을 업로드할 원격저장소를 선택해, origin이란 이름을 붙힌다.

   git push origin master
   git이 origin이란 이름을 가진 원격저장소에, master 브랜치를 사용해 커밋을 업로드한다.

   git remote remove origin
   git이 origin이란 이름을 가진 원격저장소를 삭제한다. (로컬파일에서)

3. npm install styled-components react-navigation
   styled-components를 사용해, 스타일을 가진 HTML태그를 함수처럼 사용할 수 있다.
   react-navigation을 사용해,
   graphql
   @apollo/client
   apollo-boost

4. npm install @expo/vector-icons