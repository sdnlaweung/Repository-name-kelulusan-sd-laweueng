function tampilkanConfetti() {

    const duration = 5000;
    const animationEnd = Date.now() + duration;

    const interval = setInterval(() => {

        if (Date.now() > animationEnd) {
            clearInterval(interval);
            return;
        }

        confetti({
            particleCount: 5,
            startVelocity: 30,
            spread: 360,
            ticks: 60,
            origin: {
                x: Math.random(),
                y: Math.random() - 0.2
            }
        });

    }, 150);
}