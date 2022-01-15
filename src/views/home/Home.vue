<template>
  <div>
    <top-navigation />
    <side-bar />
    <div class="row">
      <nav class="col-md-2 d-none d-md-block bg-light sidebar">
        <left-content />
      </nav>
      <main role="main" class="col-md-9 ml-sm-auto col-lg-10 pt-3 px-4">
        <right-content />
      </main>
    </div>
  </div>
</template>
<script src="./home.js"></script>
