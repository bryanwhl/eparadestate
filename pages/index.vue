<template>
  <section class="section">
    <ParadeForm> </ParadeForm>
    <PresentCounter> </PresentCounter>
  </section>
</template>

<script>
import ParadeForm from "~/components/ParadeForm";
import PresentCounter from "~/components/PresentCounter";

export default {
  name: "HomePage",

  components: {
    ParadeForm,
    PresentCounter
  }
};
</script>
