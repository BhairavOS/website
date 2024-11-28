<template>
  <div class="feature-card-container">
    <img :alt="imageAlt" :src="imageSrc" class="feature-card-image" />
    <h5 class="feature-card-text1 HeadingThree">{{ newProp }}</h5>
    <span class="feature-card-text2">{{ text }}</span>
  </div>
</template>

<script>
export default {
  name: 'FeatureCard',
  props: {
    imageSrc: {
      type: String,
      default: '/rocket1.svg',
    },
    imageAlt: {
      type: String,
      default: 'image',
    },
    text: {
      type: String,
      default: 'Our system promotes a collaborative environment in which collective brilliance results in ground-breaking ideas.',
    },
    newProp: {
      type: String,
      default: 'Design',
    },
  },
}
</script>

<style scoped>
.feature-card-container {
  flex: 0 0 auto;
  width: 25%;
  display: flex;
  margin-top: var(--dl-space-space-triplequarterunit);
  align-items: center;
  padding-left: var(--dl-space-space-triplequarterunit);
  padding-right: var(--dl-space-space-triplequarterunit);
  flex-direction: column;
}
.feature-card-image {
  height: 30px;
  object-fit: cover;
  margin-bottom: var(--dl-space-space-unitandahalfunit);
}
.feature-card-text1 {
  color: var(--dl-color-secondary-600);
  margin-top: var(--dl-space-space-halfunit);
  text-align: center;
  margin-bottom: var(--dl-space-space-halfunit);
}
.feature-card-text2 {
  text-align: center;
  margin-bottom: var(--dl-space-space-unit);
}
@media(max-width: 767px) {
  .feature-card-container {
    width: 50%;
  }
}
@media(max-width: 479px) {
  .feature-card-container {
    width: 100%;
  }
}
</style>
