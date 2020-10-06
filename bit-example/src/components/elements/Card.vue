<template>
  <div class="card">
  <img src="https://images.unsplash.com/photo-1601994588012-d46801b47f38?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=3488&q=80" alt="Avatar" style="width:100%">
    <div class="container">
      <h4><b>John Doe</b></h4>
      <p>Architect & Engineer</p>
    </div>
</div>
</template>

<script>
export default {
  name: 'ProgressBar',
};
</script>

<style>
.card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
}

.card,img {
  max-width: 450px;
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

.container {
  padding: 2px 16px;
}
</style>
