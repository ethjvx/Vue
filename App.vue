<template>
  <div class="app">
    <!-- <date-picker :date="date" @choose-date="chooseDate" /> -->
    <date-picker v-model="date" />
  </div>
</template>

<script>
import DatePicker from "./DatePicker";

export default {
  components: {
    DatePicker
  },
  data() {
    return {
      date: new Date()
    };
  }
  // methods: {
  //   chooseDate(date1) {
  //     console.log(this.date)
  //     this.date = date1;
  //   }
  // }
};
</script>

<style scoped>
</style>