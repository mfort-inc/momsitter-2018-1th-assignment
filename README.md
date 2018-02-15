# Momsitter 2018 Frontend Coding Assignment

## Description

맘편한세상 프론트엔드 개발자 지원자를 위한 코딩과제입니다. 본 과제에서는 몇가지 간단한 기능 혹은 UI/UX 등을 구현하게 됩니다.

## Tools

아래는 본 과제에서 사용할 수 있는 몇가지 툴의 예시입니다.
과제구현에 직접적인 영향을 줄 수 있는 라이브러리나 UI 프레임워크를 가져다 쓰는 것은 본 과제에서는 제한됩니다.
지원자분이 특정 툴을 사용해도 되는지에 대한 여부는 담당자에게 자유롭게 질의해주시면 됩니다.

* [React](https://reactjs.org/)
* [Redux](https://redux.js.org/)
* [create-react-app](https://github.com/facebook/create-react-app)
* [moment](https://momentjs.com/)
* [less](http://lesscss.org/)

아래는 과제의 솔루션 자체를 제공할 수 있는 툴의 예시입니다. 아래의 툴 사용은 제한됩니다.

* [material-ui](http://www.material-ui.com/#/)
* [react-autosuggest](http://react-autosuggest.js.org/)
* [jQuery UI](https://jqueryui.com/)

## Requirements

주소 입력 박스에 입력되는 키워드를 이용하여 자동완성 기능을 구현하는 문제입니다.
사용자는 주소 입력 박스에 키워드를 입력하고 해당 키워드에 매칭되는 주소 리스트를 입력 박스
하단에 노출 시킵니다. 사용자는 노출된 리스트 중 하나를 선택해서 주소를 자동 완성 시킬 수 있습니다.

사용자가 입력할 수 있는 키워드의 예는 다음과 같습니다.

* 시, 도, 구, 군 단위의 지역 키워드. (예, 성북구, 부산시, 고성군)
* 시, 도, 구, 군 단위의 지역 키워드 조합. (예, 성북구 안암동, 강원도 고성군)

필수적으로 구현해야 할 기능리스트는 다음과 같습니다.

* 사용자가 키워드 입력시 자동 완성 가능한 주소 리스트를 노출. (노출 개수는 자유)

* 자동 완성 리스트를 마우스로 클릭시, 입력 박스에 자동 완성된 주소를 적용해줌.

* 입력 박스가 포커스된 상태에서 키보드 상하 방향키를 이용해서 자동 완성 리스트를 선택할 수 있게 하기.

* 키워드가 입력되어 있고, 자동 완성 리스트가 노출되어 있는 상태에서 엔터키를 입력하면 자동 완성 리스트의
가장 상단에 노출된 항목을 자동을 선택할 수 있도록 구현.

* 입력 박스가 포커스를 잃을 때, 노출되어 있던 자동 완성 리스트가 보이지 않도록 구현.

## Bonus (Optional)

보너스 항목은 의무적으로 구현해야 하는 사항은 아닙니다!
하지만 개선되어야 할 점, 추가되면 좋을 기능, 그 밖의 지원자분의 아이디어 등을 추가적으로 구현했을 때
평가 기준에 더하여 보너스 포인트를 받을 수 있는 점입니다. 아래는 예시입니다.

* 성능을 개선 시킬 수 있는 점에 대한 고려
* 심미적으로 보일 수 있는 적절한 애니메이션
* 요구사항에 리스팅되지 않은 추가적인 기능
* 그 밖의 과제에 플러스 요인이 될 수 있는 요소 (너무나 다양합니다)

## Evaluation Criteria

지원자분이 구현한 코드를 바탕으로 어떤점이 잘되었고 어떤점이 미흡한지 체크해보게 됩니다.

1. 주어진 요구사항을 만족하는가
2. 재사용성, 퍼포먼스, 확장 가능성, 접근성 등
3. 코드의 가독성, 클린한 마크업 & 자바스크립트
2. 적절한 CSS 의 사용

## Help & Support

맘편한세상 개발팀은 인더스트리의 많은 문제들이 개인의 힘에 더해서 팀원의 힘으로 해결 할 수 있으며,
또한 그렇게 되어야 하는 것들이 많다고 생각합니다.
코딩의 직접적인 솔루션에 대한 도움을 어려울 수 있지만 그 밖의 어려움이나 도움이 필요할 때는 언제든지
담당자에게 연락을 주세요.
어쩌면 지원자분이 생각하는 아이디어가 구상만으로 그치기에는 너무나도 아까울 수 있습니다. :)

## Feedback

맘편한세상은 항상 지원자분의 의견을 듣고 개선해나가기 위해 끊임없이 노력하고 있습니다.
코딩과제를 수행하시면서 생각하신 의견이 있으시다면 언제든지 저희 담당자에게 알려주시면 감사하겠습니다!
