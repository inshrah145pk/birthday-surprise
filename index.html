/*=========================================
        Happy Birthday Alisha
        Premium Birthday Website
=========================================*/

const openBtn = document.getElementById("openBtn");
const welcomeScreen = document.getElementById("welcomeScreen");
const birthdayPage = document.getElementById("birthdayPage");
const music = document.getElementById("birthdayMusic") || null;
const typewriter = document.getElementById("typewriter");
const confettiContainer = document.getElementById("confetti-container");

/*==================================
        Open Surprise
==================================*/

openBtn.addEventListener("click", () => {

    welcomeScreen.style.opacity = "0";
    welcomeScreen.style.transition = "1s";

    setTimeout(() => {

        welcomeScreen.style.display = "none";

        birthdayPage.style.display = "block";

        birthdayPage.classList.add("fade-show");

       document.addEventListener("visibilitychange", () => {

    if (music) {
        if (document.hidden) {
            music.pause();
        } else {
            music.play().catch(() => {});
        }
    }

});
        startTypewriter();

        createConfetti();

    }, 900);

});

/*==================================
        Typewriter Text
==================================*/

let index = 0;

function startTypewriter() {

    typewriter.innerHTML = "";

    function typing() {

        if (index < birthdayText.length) {

            typewriter.innerHTML += birthdayText.charAt(index);

            index++;

            setTimeout(typing, 40);

        }

    }

    typing();

}

/*==================================
        Confetti Colors
==================================*/

const colors = [

    "#ff006e",
    "#3a86ff",
    "#00b4d8",
    "#90e0ef",
    "#ffd60a",
    "#06d6a0",
    "#fb5607",
    "#8338ec",
    "#ffffff"

];

/*==================================
        Create Confetti
==================================*/

function createConfetti() {

    for (let i = 0; i < 180; i++) {

        const piece = document.createElement("div");

        piece.className = "confetti";

        piece.style.left = Math.random() * 100 + "%";

        piece.style.background =
            colors[Math.floor(Math.random() * colors.length)];

        piece.style.animationDuration =
            (3 + Math.random() * 4) + "s";

        piece.style.animationDelay =
            Math.random() * 2 + "s";

        piece.style.opacity = Math.random();

        piece.style.transform =
            `rotate(${Math.random() * 360}deg)`;

        confettiContainer.appendChild(piece);

    }

}
/*==================================
        Continuous Confetti
==================================*/

setInterval(() => {

    if (birthdayPage.style.display === "block") {

        createMiniConfetti();

    }

}, 1200);

function createMiniConfetti() {

    for (let i = 0; i < 25; i++) {

        const piece = document.createElement("div");

        piece.className = "confetti";

        piece.style.left = Math.random() * 100 + "%";

        piece.style.background =
            colors[Math.floor(Math.random() * colors.length)];

        piece.style.animationDuration =
            (2 + Math.random() * 2) + "s";

        piece.style.opacity = Math.random();

        confettiContainer.appendChild(piece);

        setTimeout(() => {

            piece.remove();

        }, 5000);

    }

}

/*==================================
        Gift Box Animation
==================================*/

const giftLid = document.querySelector(".lid");

const giftBox = document.querySelector(".gift-box");

let giftOpened = false;

giftBox.addEventListener("click", () => {

    if (giftOpened) return;

    giftOpened = true;

    giftLid.style.transition = "0.8s";

    giftLid.style.transform =
        "translateY(-55px) rotate(-18deg)";

    giftBox.style.transform = "scale(1.08)";

    setTimeout(() => {

        giftBox.style.transform = "scale(1)";

    }, 500);

});

/*==================================
        Floating Hearts
==================================*/

function createHeart() {

    const heart = document.createElement("div");

    heart.innerHTML = "❤️";

    heart.style.position = "fixed";

    heart.style.left = Math.random() * 100 + "vw";

    heart.style.bottom = "-30px";

    heart.style.fontSize =
        (18 + Math.random() * 20) + "px";

    heart.style.pointerEvents = "none";

    heart.style.zIndex = "999";

    heart.style.transition = "transform linear";

    document.body.appendChild(heart);

    let position = 0;

    const move = setInterval(() => {

        position += 3;

        heart.style.transform =
            `translateY(-${position}px)`;

        heart.style.opacity =
            1 - (position / 700);

        if (position > 700) {

            clearInterval(move);

            heart.remove();

        }

    }, 20);

}

setInterval(() => {

    if (birthdayPage.style.display === "block") {

        createHeart();

    }

}, 1500);

/*==================================
        Sparkle Effect
==================================*/

function sparkle() {

    document.body.animate(

        [

            {

                filter: "brightness(1)"

            },

            {

                filter: "brightness(1.08)"

            },

            {

                filter: "brightness(1)"

            }

        ],

        {

            duration: 1000

        }

    );

}

setInterval(() => {

    if (birthdayPage.style.display === "block") {

        sparkle();

    }

}, 4000);
/*==================================
        Auto Scroll Animation
==================================*/

function smoothReveal() {

    const elements = document.querySelectorAll(
        ".message-box, .dua-box, .card, .quote, footer"
    );

    const observer = new IntersectionObserver((entries) => {

        entries.forEach(entry => {

            if (entry.isIntersecting) {

                entry.target.classList.add("fade-show");

            }

        });

    }, {
        threshold: 0.2
    });

    elements.forEach(el => observer.observe(el));

}

window.addEventListener("load", smoothReveal);

/*==================================
        Remove Old Confetti
==================================*/

setInterval(() => {

    const confetti = document.querySelectorAll(".confetti");

    if (confetti.length > 250) {

        for (let i = 0; i < 80; i++) {

            if (confetti[i]) {

                confetti[i].remove();

            }

        }

    }

}, 5000);

/*==================================
        Music Restart Safety
==================================*/

music.addEventListener("ended", () => {

    music.currentTime = 0;

    music.play().catch(() => {});

});

/*==================================
        Page Visibility
==================================*/

document.addEventListener("visibilitychange", () => {

    if (document.hidden) {

        music.pause();

    } else {

        music.play().catch(() => {});

    }

});

/*==================================
        Welcome Console Message
==================================*/

console.log(`
====================================

🎉 Happy Birthday Alish ❤️

Made with Love by Your Bestie ❤️

Have a wonderful birthday!

====================================
`);

/*==================================
        Final Glow Effect
==================================*/

setInterval(() => {

    const heading = document.querySelector(".mainHeading");

    if (!heading) return;

    heading.animate(

        [
            {
                transform: "scale(1)"
            },
            {
                transform: "scale(1.03)"
            },
            {
                transform: "scale(1)"
            }
        ],

        {
            duration: 1800
        }

    );

}, 2500);

/*==================================
        Finish
==================================*/

window.onload = () => {

    document.body.style.opacity = "1";

};