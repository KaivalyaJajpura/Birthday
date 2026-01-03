/* =============== CELEBRATION ICONS =============== */


.celebration-random {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: 1000;
}

.celebration-random .cake {
  position: absolute;
  font-size: 2.2rem;
  animation: bounce 2s infinite;
  filter: drop-shadow(0 0 8px #fff0f0);
  pointer-events: none;
  text-shadow: 0 0 6px #fff, 0 0 2px #fff;
}
.celebration-random .popper {
  position: absolute;
  font-size: 2rem;
  animation: popperDance 1.5s infinite alternate;
  filter: drop-shadow(0 0 8px #fffbe6);
  pointer-events: none;
  text-shadow: 0 0 6px #fff, 0 0 2px #fff;
}

@keyframes bounce {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-18px); }
}

@keyframes popperDance {
  0% { transform: rotate(-10deg) scale(1); }
  50% { transform: rotate(10deg) scale(1.15); }
  100% { transform: rotate(-10deg) scale(1); }
}
/* @import url('https://fonts.googleapis.com/css2?family=Comic+Neue&display=swap'); */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Comic Sans MS", "Comic Sans", cursive;
}

body {
  background: #ffffff;
  color: rgb(255, 255, 255);
}

/* Hide empty photos section */
.photos {
  display: none;
}

/* ================= HERO SECTION ================= */
.hero {
  position: relative;
  min-height: 100vh;
  text-align: center;
  padding-top: 120px;
  overflow: hidden;
  background: linear-gradient(to bottom, #f091de, #7affff);

}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 10px;
  text-shadow: 0 0 15px rgba(68, 66, 66, 0.6);
}

.hero p {
  font-size: 1.2rem;
  opacity: 0.9;
}

/* ================= STARS ================= */
.stars {
  position: absolute;
  inset: 0;
  width: 100vw;
  height: 100vh;
  pointer-events: none;
  z-index: 1;
}

.star {
  position: absolute;
  background: radial-gradient(circle, #fffbe6 60%, transparent 100%);
  border-radius: 50%;
  opacity: 0.8;
  box-shadow: 0 0 6px 2px #fffbe6, 0 0 12px 4px #fffbe644;
  animation: twinkle 4s infinite alternate;
}

.spark {
  position: absolute;
  background: radial-gradient(circle, #d4ff29 60%, transparent 100%);
  border-radius: 50%;
  opacity: 0.7;
  animation: sparkleFloat linear infinite;
}

@keyframes twinkle {
  from { opacity: 0.4; }
  to { opacity: 1; }
}

/* ================= SPARKLES ================= */
.sparkles {
  position: absolute;
  inset: 0;
  pointer-events: none;
  z-index: 2;
}

.sparkles span {
  position: absolute;
  width: 6px;
  height: 6px;
  background: radial-gradient(circle, #d4ff29, transparent);
  border-radius: 50%;
  opacity: 0;
  animation: sparkleFloat linear infinite;
}

@keyframes sparkleFloat {
  0% {
    transform: translateY(0) scale(0.4);
    opacity: 0;
  }
  30% {
    opacity: 1;
  }
  100% {
    transform: translateY(-120vh) scale(1.2);
    opacity: 0;
  }
}

/* ================= NOTE SECTION ================= */
/* .note {
  padding: 80px 20px;
  background: #7c63ea;
  text-align: center;
} */

.note h2 {
  font-size: 2rem;
  margin-top: 100px;
  text-align: center;
  position: relative;
}

.note-card {
  max-width: 600px;
  margin: auto;
  background: #fff0ff;  
  padding: 30px;
  border-radius: 12px;
  line-height: 1.7;
  color: rgb(103, 50, 156);
  /* font-family: "Comic Neue", cursive !important; */

  
}


/* ================= FLOATING PARTY ELEMENTS ================= */
.floating-elements {
  position: absolute;
  inset: 0;
  pointer-events: none;
  z-index: 3;
}

.floating {
  position: absolute;
  font-size: 1.8rem;
  animation: floatUp linear infinite;
  opacity: 0;
  filter: drop-shadow(0 0 8px rgba(255,255,255,0.8));
}

body {
  margin: 0;
  background: linear-gradient(to bottom, #f091de, #7affff);
  color: rgb(255, 255, 255);
}

@keyframes floatUp {
  0% {
    transform: translateY(0) scale(0.6);
    opacity: 0;
  }
  20% {
    opacity: 1;
  }
  100% {
    transform: translateY(-120vh) scale(1.2);
    opacity: 0;
  }
}

.hero h1,
.hero p,
.note {
  position: relative;
  z-index: 2000;
}

/* ================= GIFT SECTION ================= */

.gift-section {
  background: linear-gradient(to bottom, #7affff, #f091de);
  display: flex;
  flex-direction: column;
  align-items: center;

  /* IMPORTANT FIX */
  justify-content: flex-start;

  gap: 20px;
  text-align: center;
  padding: 80px 20px 60px;
  margin-top: 0;
}


.scroll-text {
  font-size: 1.5rem;
  opacity: 0.8;
}

/* Gift Box */
.gift-box {
  font-size: 4rem;
  cursor: pointer;
  transition: transform 0.3s ease;
}

.gift-box:hover {
  transform: scale(1.1);
}

/* Poem Card */
.poem-card {
  max-width: 600px;
  background: #fff0ff;
  padding: 30px;
  border-radius: 16px;
  color: rgb(103, 50, 156);
  line-height: 1.8;
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);
  animation: popIn 0.6s ease forwards;
}

/* Hidden initially */
.hidden {
  display: none;
}

/* Animation */
@keyframes popIn {
  0% {
    transform: scale(0.7);
    opacity: 0;
  }
  100% {
    transform: scale(1);
    opacity: 1;
  }
}


.gift-section {
  position: relative;
  overflow: hidden; /* IMPORTANT */
}

/* Keep gift content above effects */
.gift-section > *:not(.stars):not(.sparkles):not(.celebration-random):not(.floating-elements) {
  position: relative;
  z-index: 10;
}


/* ================= MOBILE RESPONSIVENESS ================= */
@media (max-width: 768px) {

  /* HERO SECTION */
  .hero {
    padding-top: 80px;
  }

  .hero h1 {
    font-size: 2.2rem;
    padding: 0 12px;
  }

  .hero p {
    font-size: 1rem;
    padding: 0 14px;
  }

  /* NOTE SECTION */
  .note h2 {
    font-size: 1.6rem;
    margin-top: 60px;
  }

  .note-card {
    width: 90%;
    padding: 22px;
    font-size: 0.95rem;
  }

  /* GIFT SECTION */
  .gift-section {
    padding: 60px 16px 50px;
  }

  .scroll-text {
    font-size: 1rem;
  }

  .gift-box {
    font-size: 3.2rem;
  }

  /* POEM CARD */
  .poem-card {
    width: 92%;
    padding: 22px;
    font-size: 0.95rem;
  }

  .poem-card h2 {
    font-size: 1.4rem;
  }

  /* EFFECTS: reduce clutter on mobile */
  .floating,
  .cake,
  .popper {
    font-size: 1.4rem;
    opacity: 0.75;
  }
}
