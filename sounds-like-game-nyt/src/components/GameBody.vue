<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <h1>Sounds Like.. Game!</h1>
  <p>
    You need to guess four words that all sound similar to each other.
    Each word has a clue - all you have to do is find the group of words that
    rhyme or partially rhyme with each other.
  </p>
  <br />
  <div class="clue-guess">
    <h2>Airplane</h2>
    <input id="guess-1" />
    <div class="right-wrong-guesses">
    </div>
  </div>
  <div class="clue-guess">
    <h2>Vaccine</h2>
    <input id="guess-2" />
    <div class="right-wrong-guesses">
    </div>
  </div>
  <div class="clue-guess">
    <h2>Theme park</h2>
    <input id="guess-3" />
    <div class="right-wrong-guesses">
    </div>
  </div>
  <div class="clue-guess">
    <h2>__ = 0 (int)</h2>
    <input id="guess-4" />
    <div class="right-wrong-guesses">
    </div>
  </div>
</template>

<style>
.clue-guess {
  display: flex;
  justify-content: space-between;
  width: 50%;
  margin: 10px 0;
}


</style>
