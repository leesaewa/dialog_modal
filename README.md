# dialog_modal
- `html`의 `dialog` 태그를 사용하여 모달을 구현하기
- `dialog` 기능 알기


## 코드

```
const openBtn = document.getElementById("openBtn"); // 클릭하면 dialog가 열리는 버튼
const dialog = document.querySelector("dialog");

openBtn.addEventListener("click", () => {
  dialog.showModal(); // 버튼을 클릭하면 dialog가 오픈됨
});
```

## 추가할 것
- `backdrop` 클릭 시, `dialog` 닫기
