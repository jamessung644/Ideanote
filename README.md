# 💡 아이디어 보드 README.md

## ❓ 아이디어 보드가 뭐예요?
**아이디어 보드**는 사용자가 간단하게 아이디어를 작성하고, 공유하며, 좋아요를 누를 수 있는 웹 애플리케이션입니다. Vue.js와 Firebase를 사용하여 실시간으로 아이디어를 추가하고, 수정하며, 삭제할 수 있습니다. TailwindCSS로 디자인되어 직관적이고 반응형으로 제작되었습니다.

## 🙋‍♀️ 어떻게 사용하나요?
1. **아이디어 추가하기**: 상단 입력란에 제목과 아이디어 내용을 입력하고 '추가' 버튼을 클릭하세요.
2. **아이디어 보기**: 아이디어 카드를 클릭하면 팝업 창이 열리고, 해당 아이디어의 상세 내용을 확인할 수 있습니다.
3. **좋아요 누르기**: 아이디어 팝업 창에서 '좋아요' 버튼을 클릭하면 해당 아이디어에 좋아요를 표시할 수 있습니다.
4. **아이디어 삭제하기**: 본인이 작성한 아이디어는 삭제할 수 있습니다.

## 🛠 기능 엿보기
1. [Header](#header)
2. [Text Style1](#text-style1)
3. [Text Stlye2](#text-style2)
4. [List](#list)
5. [Link](#link)
6. [Code Block](#code-block)
7. [Table](#table)

### Header
- **아이디어 보드**의 제목은 H1으로 설정되었습니다.
- **아이디어 카드**의 제목은 H2로 설정되었습니다.

### Text Style1
- **굵게**: 아이디어 제목과 버튼 텍스트에 굵게 스타일이 적용되었습니다.
- **기울이기**: 필요에 따라 추가 가능합니다.
- **취소선**: 삭제된 아이디어를 표시할 때 사용될 수 있습니다.
- **밑줄**: 강조할 텍스트에 사용될 수 있습니다.

### Text Style2
> 인용문: 팝업 창 내부에 텍스트 강조를 위해 사용될 수 있습니다.

### List
- **Table of contents**: 기능들을 목록으로 표시합니다.
- **Unordered list**: 아이디어를 나열할 때 사용됩니다.
- **Ordered list**: 단계적인 절차 설명에 사용될 수 있습니다.

### Link
- **General link**: [🚗 Visit 아이디어 보드의 Repo](https://github.com/your-repo-link)
- **Image link**: ![아이디어 보드](./path/to/your/image.png)

### Code Block
- **Code inline**: `console.log('Hello 아이디어 보드!');`
- **Code block**:
```js
const app = initializeApp(firebaseConfig);
const db = getFirestore(app);
