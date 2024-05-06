<template>
  <div class="outer-box">
    <h2>Selamat Datang di Aplikasi</h2>
    <div class="home">
      <p>Aplikasi ini dibuat oleh:</p>
      <ul>
        <li>NPM: 40622100120</li>
        <li>NAMA: Aulia Nur Fadilah</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeFrom'
}
</script>

<style scoped>
h2 {
  border-bottom: 1px solid #ccc;
  padding-bottom: 15px;
}

.outer-box {
  border: 1px solid #ccc;
  padding: 20px;
  width: 300px;
  height: 200px;
  position: absolute;
  top: 0;
  left: 0;
  margin-top: 100px;
  margin-left: 275px;
  width: 390px;
  height: 200px;
}

.home {
  margin-top: 20px;
}
</style>
