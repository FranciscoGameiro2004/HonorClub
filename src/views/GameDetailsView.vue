<template>
  <TeamButton />
  <DetailedResults/>
  <TeamButton/>
  <SummarySection/>
</template>

<script>
import TeamButton from '@/components/TeamButton.vue'
import DetailedResults from '@/components/DetailedResults.vue';
import SummarySection from '@/components/SummarySection.vue';
export default {
    components: {
        TeamButton,
        DetailedResults,
        SummarySection,
    },
}
</script>

<style>

</style>