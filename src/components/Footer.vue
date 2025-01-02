<script lang="ts">
export default {
  name: "Footer"
}
</script>

<template>
  <footer class="footer">
    <div class="content">
      <ul class="links">
        <li><a href="#" class="icon">Facebook</a></li>
        <li><a href="#" class="icon">Twitter</a></li>
        <li><a href="#" class="icon">Instagram</a></li>
        <li><a href="#" class="icon">Telefónne číslo</a></li>
      </ul>
      <div class="bottom">
        <p>&copy; 2024 Michal Smatana. Vlastnoručne vyrobené. </p>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer{
  background-color: #0c0c0c;
  color: #fff;
  padding: 2rem;
}
.content{
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  gap: 1rem;
}
.links{
  display: flex;
  justify-content: center;
  gap: 3rem;
  flex-wrap: wrap;
}
.icon{
  color: #fff;
  font-size: 1.5rem;
  transition: color 0.3s ease;
}
.bottom{
  text-align: center;
  margin-top: 2rem;
}
</style>