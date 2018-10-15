<template>
  <div>
    <h1>{{ part.title }}</h1>
    <div>
      {{ part.description }}
    </div>
  </div>
</template>

<script>
// import parts from '../data/parts';

export default {
  name: 'PartInfo',
  data() {
    return {
      part: {
        title: 'Part Title',
        description: 'Part Description',
      },
    };
  },
};
</script>

