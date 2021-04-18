<template>
  <div class="note-selectors">
    <NoteSelectors />
    <NoteSelectors />
    <NoteSelectors />
  </div> 
</template>

<script>
import NoteSelectors from "./NoteSelectors.vue";
export default {
  name: "noteselector",
  components: {
    NoteSelectors,
  },
};
</script>