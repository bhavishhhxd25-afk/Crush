document.getElementById('yesBtn').addEventListener('click', function() {
    document.getElementById('response').innerText = "Yay! I love you! 🎉";
});

document.getElementById('noBtn').addEventListener('click', function() {
    document.getElementById('response').innerText = "Are you sure? 😢 (Try again!)";
    // Optional: Make it move away for fun
    this.style.position = 'relative';
    this.style.left = Math.random() * 200 + 'px';
});
