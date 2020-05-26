![JavaScript Card Quiz](/images/card-quiz.png)

> 🚨과제를 시작하는 방법과 제출하는 방법은 [과제 관련 안내](https://www.notion.so/vanillacoding/9b7bb71aa95f4bd4906e7496d6ad8db3) 페이지에서 찾을 수 있습니다.

# JavaScript Card Quiz Project

자바스크립트를 공부하는 사람들을 위해 카드 형식의 퀴즈를 만들어 보는 과제입니다. 아래에는 예시 UI입니다.

![Sample Quiz](/images/sample.png)

데이터를 이용해 UI작업을 하는 연습과 함께 퀴즈 내용에 나온 문제들도 마스터해보세요 🎖

- **반드시 아래 Setup과 Development 부분을 읽어보세요.**
- 과제를 시작하는 방법과 제출하는 방법은 [과제 관련 안내](https://www.notion.so/vanillacoding/9b7bb71aa95f4bd4906e7496d6ad8db3) 페이지에서 찾을 수 있습니다.
- 상세 요구 사항은 아래 TODO 파트를 참고하세요.

## Setup (사전 설치)

Install dependencies

```sh
$ npm install
```

## Development (작업 방법)

```sh
$ npm run dev
# Visit http://localhost:1234 from your browser (Chrome)
```

ℹ️ [npm custom script](https://stackoverflow.com/questions/36433461/how-do-i-add-a-custom-script-to-my-package-json-file-that-runs-a-javascript-file)

- HTML: `index.html`를 수정하세요.
- JS: `/app/index.js`를 수정하세요.
- CSS: `/styles/index.css`를 수정하세요.
- Images: `/images` 디렉토리를 이용하세요.

## TODO

스타일이나 아래에 명시되지 않은 기능은 재량껏 구현해주시기 바랍니다. 애니메이션이나 시각적인 효과는 중요하지 않지만, 시간이 되면 시도해보세요.

- [ ] 퀴즈를 시작할 수 있는 버튼이 보여야 합니다.
- [ ] 사용자가 시작 버튼을 눌렀을 경우, `quiz.json`의 첫 문제부터 카드 형식으로 보여주어야 합니다.
- [ ] 사용자가 현재까지 맞춘 정답의 갯수와 남은 문제의 숫자를 화면에 표기해주어야 합니다.
- [ ] 문제에 따라 예제 코드가 있다면, 함께 보여주어야 합니다.
- [ ] 문제의 정답을 맞출 경우, 정답이라고 표기해주고 다음 문제로 진행할 수 있는 버튼이 나타나야 합니다.
- [ ] 문제의 정답을 맞추지 못했을 경우, 정답을 표기해주고 다음 문제로 진행할 수 있는 버튼이 나타나야 합니다.
- [ ] 마지막 문제가 끝났을 경우, 수고했다는 메시지와 함께 재시작 버튼이 나타나야 합니다.
- [ ] 재시작 버튼을 눌렀을 경우, 다시 처음부터 위 단계를 반복할 수 있어야 합니다.

### Advanced

- [ ] 한 문제에 대한 제한 시간을 두고, 제한 시간 내에 정답을 맞추지 못했을 경우 오답 처리하는 기능을 추가해보세요.
