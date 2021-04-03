# vue-todo

## Project setup
```
intellij tool vue 프로젝트 선택
```

### Project Structure
```
TodoHeader: 타이틀 정보 컴포넌트
TodoInput: 텍스트 입력 및 로컬 스토리지 저장 컴포넌트 
TodoList: 저장한 할일 목록 보여주는 컴포넌트
TodoFooter: 전체 리스트 삭제
```

### Project Description
```
1. input 박스에 저장할 값을 입력 후 +버튼(엔터) 눌러 생성
2. 입력한 내용을 LocalStorage에 저장 후 리스트 출력
3. 리스트내 삭제 버튼 클릭할 때 LocalStorage 데이터 삭제 후 리스트 삭제
4. ClearAll버튼 클릭시 LocalStorage 데이터 삭제 후  리스트 목록 삭제
5. Input 박스에 데이터 없이 +버튼(엔터) 누르면 모달 출력
```

### Issue or Bug
```
모달 css 제대로 생성되지 않음. z-index 문제 있음
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
