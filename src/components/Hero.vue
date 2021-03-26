<template>
  <div class="hero">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="hero-details d-flex align-items-center">
            <h1 class="text-left font-weight-bold">
              &lt;Hi, you found me! I am a front-end developer from Brazil.
              Currently working to build awesome things. / &gt;
            </h1>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style>
.hero{
  background-color: #111212;
  color: #fff;
  font-family: 'Roboto', sans-serif;  
}
.hero-details{
  height: 55rem;
  font-size: 5rem;
}

</style>
