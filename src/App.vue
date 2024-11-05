<script setup>
// No necesitamos importar HelloWorld para esta página
import '@fortawesome/fontawesome-free/css/all.css';
</script>

<template>
  <div class="construction-page">
    <h1>Sitio Web en Construcción</h1>
    <div class="construction-icon">
      🚧
    </div>
    <p>Estamos trabajando para traerte algo increíble.</p>
    <p>¡Vuelve pronto!</p>
    <footer class="social-footer">
      <div class="social-links">
        <a href="https://www.instagram.com/xortechnology/profilecard/?igsh=MTkwOHpiNDA5azhwaA==" target="_blank" class="social-link"> 
          <i class="fab fa-instagram"></i>
        </a>
        <a href="https://www.linkedin.com/in/brandon-rivera-179a2bb6/" target="_blank" class="social-link">
          <i class="fab fa-linkedin"></i>
        </a>
      </div>
    </footer>
  </div>
</template>

<style scoped>
.construction-page {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 2rem;
  background-color: #242424;
}

h1 {
  color: #cdcccc;
  margin-bottom: 2rem;
  font-size: 2.5rem;
}

.construction-icon {
  font-size: 5rem;
  margin: 2rem 0;
  animation: bounce 2s infinite;
}

p {
  color: #cdcccc;
  font-size: 1.2rem;
  margin: 0.5rem 0;
}

.social-footer {
  margin-top: 2rem;
  width: 100%;
}

.social-links {
  display: flex;
  justify-content: center;
  gap: 1rem;
}

.social-link {
  color: #cdcccc;
  font-size: 1.5rem;
  transition: color 0.3s ease;
}

.social-link:hover {
  color: #646cff;
}

@keyframes bounce {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-20px);
  }
}
</style>
