# VS CODE(Visual Studio Code)
역시 MS인가 Type Script도 배워보고 싶을 정도로 VSCode는 정말 굉장하다..

## 단축키
- F12 // Go To Declaration 선언한 곳으로 찾아가줌. ctags 처럼도 이용 가능(C/C++ 확장프로그램 설치)
- Shift + F12 // 모든 참조 찾기
- Alt + F12 // Picking Definition 은 왜쓰는지 모르겠네 Shift 가 나은거 같은데
- Alt + <- // 이전에 보던 라인, undo랑 비슷
- Alt + -> // 다음에 본 라인, redo랑 비슷

## Extensions
* Atom Keymap // Awesome!!! atom -> vscode
* Reactjs code snippets // 설명이 필요있나 rcc tab!
* View In Browser // Ctrl + F1
* Debugger for Chrome // line number 옆에 클릭하면 debug break point
* Project Manager // F1 -> project * //list = shift+alt+p
* HTML
  * HTML Snippets
  * HTML CSS Class Completion
* jshint
* ESLint
* Git History // F1 -> View History(git log)

## Own Snippets(파일->기본설정->사용자 코드조각)

### JavaScript
```json
{
	"Print to console": {
		"prefix": "log",
		"body": [
			"console.log('$1');",
			"$2"
		],
		"description": "Log output to console"
	},
	"TS Console Log": {
		"prefix": "tlg",
		"body": [
			"console.log('[TS_LOG] $1 : ' + $1);",
			"$2"
		],
		"description": "Log output to console"
	}
}
```