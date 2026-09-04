프로젝트명 : AI를 활용한 자기소개 웹페이지(web-dev-assignment)

프로젝트에 대한 간단한 설명 : AI 도구를 활용해서 자기소개 웹페이지를 만들고 이후 직접 코드를 수정해서 index2.html을 제작하였습니다. Git과 GitHub를 이용해 변경 내용을 관리하고 Vercel을 통해 웹페이지를 배포하면서 전체적인 웹 개발 과정을 실습해보았습니다.

Vercel Deploy Main URL : https://web-dev-assignment-theta-sandy.vercel.app
index.html URL : https://web-dev-assignment-theta-sandy.vercel.app/index.html
index2.html URL : https://web-dev-assignment-theta-sandy.vercel.app/index2.html


<<Weekly Review>>

1. VS Code에서 AI를 이용한 HTML 작성과 Git으로 변경 내용을 관리한 다음 GitHub에 올리고 Vercel을 통해 배포하며 웹페이지 개발과 배포되는 전체적인 과정을 익힐 수 있었습니다.

2. AI를 활용해서 코드를 수정하고 Elements로 브라우저에서 HTML 구조와 CSS 스타일을 한눈에 보고 실시간으로 테스트해볼 수 있었습니다.

3. add → commit → push 과정을 직접 해보면서 각각의 명령어가 어떤 역할을 하는지 배웠습니다. 특히 코드를 수정한 뒤 GitHub에 다시 push하면 Vercel에서 자동으로 변경된 웹페이지가 배포되는 것도 직접 확인해보았습니다.

<Development Flow>

`VS Code` ➔ `HTML/CSS` ➔ `Git` ➔ `GitHub` ➔ `Vercel Auto Deploy` ➔ `Web Page`
이번 실습에서는 먼저 VS Code에서 AI를 활용하여 HTML를 작성하고 수정했습니다. 이후 Git을 사용해서 변경된 파일을 관리하고 GitHub Repository에 push했습니다. GitHub와 Vercel을 연결해두어서 GitHub에 변경 사항을 push하면 Vercel에서 자동으로 배포되는 과정을 확인할 수 있었습니다.

<Code Modification>

1. 프로필 이미지 변경
   기존에 AI가 넣어준 이미지 주소 대신 제가 가지고 있는 프로필 이미지 파일을 사용하도록 수정했습니다. 이미지 파일의 이름과 경로를 확인하고 `src` 부분을 변경했습니다.

2. 자기소개 내용 수정
   기존에 들어있던 내용을 제 실제 정보에 맞게 수정했습니다.

3. 색 수정
   텍스트 색을 조금 더 눈에 뛸 수 있도록 수정하였습니다.

<Problem & Solution>

실습하면서 프로필 이미지가 웹페이지에 제대로 나오지 않는 문제가 있었습니다. 확인해보니 실제 이미지 파일은 `.jpg`였는데 HTML 코드에서는 `.png`로 작성되어 있어서 이미지가 제대로 불러와지지 않았습니다. VS Code의 파일 목록에서 실제 파일 확장자를 확인한 뒤 HTML의 `src` 부분을 `.jpg`로 수정했고, 이후 이미지가 정상적으로 나타나는 것을 확인했습니다. 이 과정을 통해 파일 경로나 확장자를 정확하게 작성하는 것이 중요하다는 것을 알게 되었습니다.

<Reflection>

이번 실습을 하면서 단순히 HTML 코드를 작성하는 것뿐만 아니라 코드를 수정하고 Git으로 관리한 뒤 실제 웹페이지로 배포하는 과정까지 직접 경험해볼 수 있어서 좋았습니다. 또한 가장 중요한 `git add`, `git commit`, `git push`가 각각 어떤 의미를 가지고 있는지 직접 사용해보면서 조금 더 이해하게 되었습니다. 개발자 도구의 Elements 탭에서 CSS를 직접 바꿔보면서 웹페이지의 디자인을 바로 확인할 수 있다는 것도 새롭게 알게 되었습니다. 앞으로 다른 웹페이지를 만들 때는 AI가 만들어준 코드를 그대로 사용하는 것보다 코드를 하나씩 확인하면서 제가 원하는 방향으로 직접 수정해보고 싶습니다.