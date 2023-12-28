<div class="mainContainer">
  <div class="headerContainer">
    <h1>Todo List</h1>
    <button>Save</button>
  </div>
  <main></main>
  <div class="enterTodo">
    <input type="text" placeholder="Enter Todo" />
    <button>ADD</button>
  </div>
</div>

<style>
  .mainContainer {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
    gap: 24px;
    padding: 24px;
    width: 100%;
    max-width: 1000px;
    margin: 0 auto;
  }

  .headerContainer {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  main {
    display: flex;
    flex-direction: column;
    gap: 8px;
    flex: 1;
  }

  .enterTodo {
    display: flex;
    align-items: stretch;
    border: 1px solid white;
  }

  .enterTodo input {
    background: transparent;
    border: none;
    padding: 14px;
    color: white;
    flex: 1;
  }

  .enterTodo input:focus {
    outline: none;
  }

  .enterTodo button {
    padding: 0 14px;
    background: rgb(167, 165, 165);
    border: none;
    color: black;
    font-weight: 600;
  }
</style>
