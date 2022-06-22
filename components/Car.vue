<template>
  <div>
    <cld-image
      :public-id="publicId"
      type="fetch"
      alt="An image of a cat"
      height="400"
      width="700"
    >
      <cld-transformation radius="80" />
      <cld-transformation effect="grayscale" />
      <cld-transformation
        overlay="text:arial_60:Rimac Nevera C Two"
        gravity="south"
        y="20"
      />
    </cld-image>
  </div>
</template>

<script>
export default {
  data() {
    return {
      publicId:
        "https://cdn.luxe.digital/media/20220127155206/fastest-cars-world-2022-luxe-digital-1-1200x600.jpg.webp",
    };
  },
};
</script>
