<script>
const noBtn = document.getElementById("noBtn");
const taunt = document.getElementById("taunt");
const car = document.getElementById("car");

const taunts = [
  "Nice try 😜",
  "You can't click me 😈",
  "Too slow 😂",
  "Wrong button 😏",
  "Catch me if you can 🏎️",
  "Love is chasing you 💘",
  "Not today 😝"
];

let dodgeLoop;

// Move NO forever
function moveNo() {
  const x = Math.random() * (window.innerWidth - 180);
  const y = Math.random() * (window.innerHeight - 140);

  noBtn.style.position = "fixed";
  noBtn.style.left = x + "px";
  noBtn.style.top = y + "px";

  taunt.innerHTML = taunts[Math.floor(Math.random() * taunts.length)];
}

dodgeLoop = setInterval(moveNo, 650);

// Speed up on hover
noBtn.addEventListener("mouseenter", () => {
  clearInterval(dodgeLoop);
  dodgeLoop = setInterval(moveNo, 320);
});

// F1 CAR BACKGROUND CHASE SYSTEM
let carX = 0;
let carY = 0;
let speed = 4;

function chaseNo() {
  const rect = noBtn.getBoundingClientRect();

  const targetX = rect.left - 80;
  const targetY = rect.top - 30;

  const dx = targetX - carX;
  const dy = targetY - carY;

  const angle = Math.atan2(dy, dx);

  carX += Math.cos(angle) * speed;
  carY += Math.sin(angle) * speed;

  car.style.left = carX + "px";
  car.style.top = carY + "px";
  car.style.transform = `rotate(${angle * 57.3}deg)`;
}

setInterval(chaseNo, 20);

// YES CLICKED
function yesClicked() {
  document.querySelector("p").innerHTML =
    "🏁 YOU WIN!! My Cutie is now Your Cutie’s Valentine 💘😂";

  clearInterval(dodgeLoop);

  // Fade NO romantically
  noBtn.style.transition = "0.8s ease";
  noBtn.style.opacity = "0";
  noBtn.style.transform = "scale(0.4) rotate(30deg)";

  setTimeout(() => noBtn.remove(), 800);

  // Explosion
  for (let i = 0; i < 40; i++) {
    const spark = document.createElement("div");
    spark.className = "spark";
    spark.innerHTML = "💥";

    spark.style.left = noBtn.offsetLeft + "px";
    spark.style.top = noBtn.offsetTop + "px";

    spark.style.setProperty("--x", (Math.random() - 0.5) * 600 + "px");
    spark.style.setProperty("--y", (Math.random() - 0.5) * 500 + "px");

    document.body.appendChild(spark);
    setTimeout(() => spark.remove(), 1500);
  }

  taunt.innerHTML = "Love wins 💕🏎️😂";
}
</script>
