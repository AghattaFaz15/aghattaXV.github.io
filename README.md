body {
  margin: 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: 
    linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
    url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1600&q=80') no-repeat center center fixed;
  background-size: cover;
  color: white;
  line-height: 1.6;
  padding: 1rem 2rem 4rem;
  position: relative;
  overflow-x: hidden;
}

body::before {
  content: "Aghatta faz XV";
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%) rotate(-20deg);
  font-size: 12vw;
  color: rgba(255, 106, 0, 0.08);
  font-weight: 900;
  font-family: 'Segoe UI Black', 'Arial Black', Arial, sans-serif;
  pointer-events: none;
  user-select: none;
  z-index: 0;
}

.container {
  position: relative;
  z-index: 1;
  background-color: rgba(0, 0, 0, 0.75);
  border-radius: 12px;
  max-width: 900px;
  margin: 2rem auto;
  padding: 2rem 2.5rem;
  box-shadow: 0 0 20px #ff6a00aa;
}
