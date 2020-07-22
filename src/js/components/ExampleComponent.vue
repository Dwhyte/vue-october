<template>
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-md-8">
        <div class="card card-default">
          <div class="card-header">{{ title }}</div>

          <div class="card-body">
            You did it D!
            <p>{{ message }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    console.log("Component mounted.");
  },
  data() {
    return {
      title: "My first Vue Component",
      message: "Awesome Job Setting up Vue in October!"
    };
  }
};
</script>
