<template>
  <div class="container border border-primary p-5 rounded">
    <div class="d-flex flex-column justify-items-center align-items-center">
      <div class="mb-3 d-flex flex-column align-items-center">
        <cld-image public-id="photo-1630482517504-3ea85c10e7ba" class="mb-2">
          <cld-transformation height="80" width="80" crop="fill" />
          <cld-transformation radius="max" />
        </cld-image>
        <h5 class="mb-0">Daniel Mark</h5>
        <p>Software Engineer</p>
      </div>
      <div class="card" style="width: 288px">
        <cld-image public-id="photo-1630482517504-3ea85c10e7ba">
          <cld-transformation height="320" crop="fill" />
        </cld-image>
        <div class="card-body">
          <h5 class="card-title">Bio</h5>
          <p class="card-text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta nobis
            expedita, ipsum,
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
};
</script>

<style></style>