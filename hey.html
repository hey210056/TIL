<html>

<head>
  <title>Mission 1</title>
  <meta charset="utf-8" />
</head>

<body>
  <div id="todo-list"></div>
  <div id="daily-list"></div>
  <div id="weekly-list"></div>
  <script>
    const data = [
      {
        text: 'JS 공부하기',
        isCompleted: true
      },
      {
        text: 'JS 복습하기',
        isCompleted: false
      }
    ]
    const eat = [
      {
        text: '밥 먹기',
        isCompleted: true
      },
      {
        text: '커피 마시기',
        isCompleted: true
      }
    ]
    const play = [
      {
        text: '노래 듣기',
        isCompleted: true
      },
      {
        text: '영화 보기',
        isCompleted: false
      }
    ]

    function TodoList(list, listId) {
      if (!new.target) {
        throw new Error('new 키워드 안 붙이고 함수 실행 시 에러 발생');
      }
      this.check = function (list) {
        if (list === null || list === undefined) {
          throw new Error('파라미터 값이 null이거나 undefined인 경우 에러 발생');
        } else if (Array.isArray(list) && list.length === 0) {
          throw new Error('배열이 아닌 경우 혹은 빈 배열인 경우 에러 발생');
        }
      }
      this.list = list;
      this.listId = listId;
      this.render = () => {
        document.querySelector(`#${this.listId}`).innerHTML =
          `${this.list.map((todo) => {
            return `<div>${todo.isCompleted ? `<s>${todo.text}</s>` : `${todo.text}`}</div>`
          }).join('')}`;
      }
      this.setState = (nextData) => {
        this.list = nextData;
        this.check(nextData);
        this.render();
      }

      this.render();
    };

    const todolist = new TodoList(data, "todo-list");
    const mealcheck = new TodoList(eat, "daily-list");
    const breaktime = new TodoList(play, "weekly-list");

    breaktime.setState([
      {
        text: '전시회 보고 오기',
        isCompleted: false
      }
    ]);

  </script>
</body>

</html>
