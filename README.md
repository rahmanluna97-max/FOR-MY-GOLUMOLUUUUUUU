
    <p>
      And if life is a fight, I hope you never
      have to face every round alone.
      I'll always wish for your happiness,
      success and beautiful future.
    </p>

    <p>
      You are more than just a fighter.
      You're someone with dreams, courage
      and a heart worth knowing.
    </p>

    <div class="signature">
      With endless affection,<br>
      Your Moon ♡
    </div>

    <div class="question">
      WILL YOU BE MINE??
    </div>

    <div class="final-moon">☾ ♡ ∞</div>

  </div>

  <div class="footer">
    DEEPMO • UNDER THE SAME MOON
  </div>

</div>

</div>

<script>
function unlock() {
  const password =
    document.getElementById("password").value;

  if (password === "DEEPMO") {
    document.getElementById("login").style.display = "none";
    document.getElementById("letter").style.display = "block";
    window.scrollTo({top: 0, behavior: "smooth"});
  } else {
    document.getElementById("error").innerText =
      "Wrong Password! Try Again ♡";
  }
}

document.getElementById("password")
.addEventListener("keypress", function(event) {
  if (event.key === "Enter") unlock();
});
</script>

</body>
</html>
