<template>
  <div>
    <cld-image
      :public-id="publicId"
      type="fetch"
      alt="An image of a cat"
      height="400"
      width="700"
    >
      <cld-transformation effect="vectorize" />
      <cld-transformation format="auto" />
      <cld-transformation quality="100" />
    </cld-image>
  </div>
</template>

<script>
export default {
  data() {
    return {
      publicId: "https://res.cloudinary.com/demo/image/upload/beach_huts.jpg",
    };
  },
};
</script>
