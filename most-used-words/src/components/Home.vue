<template>
  <v-container fluid>
    <div class="pills">
      <Pill
        v-for="word in groupedWords"
        :key="word.name"
        :name="word.name"
        :amount="word.amount"
      />
    </div>
  </v-container>
</template>

<script>
import Pill from "./Pill";
export default {
  components: {
    Pill,
  },
  data: function() {
    return {
      groupedWords: [
        { name: "you", amount: 900 },
        { name: "i", amount: 950 },
        { name: "he", amount: 1700 },
        { name: "wg", amount: 1 },
        { name: "you", amount: 900 },
        { name: "i", amount: 950 },
        { name: "he", amount: 1700 },
        { name: "wg", amount: 1 },
        { name: "you", amount: 900 },
        { name: "i", amount: 950 },
        { name: "he", amount: 1700 },
        { name: "wg", amount: 1 },
        { name: "you", amount: 900 },
        { name: "i", amount: 950 },
        { name: "he", amount: 1700 },
        { name: "wg", amount: 1 },
        { name: "you", amount: 900 },
        { name: "i", amount: 950 },
        { name: "he", amount: 1700 },
        { name: "wg", amount: 1 },
        { name: "you", amount: 900 },
        { name: "i", amount: 950 },
        { name: "he", amount: 1700 },
        { name: "wg", amount: 1 },
        { name: "you", amount: 900 },
        { name: "i", amount: 950 },
        { name: "he", amount: 1700 },
        { name: "wg", amount: 1 },
        { name: "you", amount: 900 },
        { name: "i", amount: 950 },
        { name: "he", amount: 1700 },
        { name: "wg", amount: 1 },
        { name: "you", amount: 900 },
        { name: "i", amount: 950 },
        { name: "he", amount: 1700 },
        { name: "wg", amount: 1 },
      ],
    };
  },
};
</script>

<style>
.pills {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
</style>
