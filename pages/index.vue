<template>
  <div class="row min-height">
    <div
      class="left col-4 full-height orange-backdrop d-grid place-content-end p-b-50"
    >
      <span>
        <img src="~/assets/images/image1.png" alt="" />
      </span>
    </div>
    <div class="right col-8 full-height">
      <div class="container">
        <div class="d-flex justify-end">
          <button class="button button-fill-red">
            <p class="p-r-5 p-l-5 p-t-2 p-b-2">Logout</p>
          </button>
        </div>

        <!-- step navigation -->
        <step-navigation class="m-t-20" />

        <hr class="m-t-15" />
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>
<style scoped>
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 42em) {
  .left {
    display: none;
  }
}
</style>
