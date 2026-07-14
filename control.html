import { subscribe, changeCount, resetCount } from "./firebase.js";

const countEl = document.querySelector("#count");
const statusEl = document.querySelector("#status");

const plusButton = document.querySelector("#plus");
const minusButton = document.querySelector("#minus");
const resetButton = document.querySelector("#reset");

function showError(error) {
  console.error(error);
  statusEl.textContent = "Błąd: " + (error?.message || "nieznany");
}

subscribe(
  (count) => {
    countEl.textContent = count;
    statusEl.textContent = "Połączono";
  },
  showError
);

plusButton.addEventListener("click", () => changeCount(1));
minusButton.addEventListener("click", () => changeCount(-1));
resetButton.addEventListener("click", () => resetCount());

window.addEventListener("keydown", (event) => {
  const key = event.key.toLowerCase();

  if (event.code === "Space" || event.key === "ArrowUp") {
    event.preventDefault();
    changeCount(1);
  } else if (event.key === "ArrowDown") {
    event.preventDefault();
    changeCount(-1);
  } else if (key === "r") {
    resetCount();
  }
});
