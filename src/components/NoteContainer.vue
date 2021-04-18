<template>
  <div class="note-container">
    <NoteSelector />
    <NoteEditor />
  </div>
</template>

<script>
import NoteSelector from "./NoteSelector.vue";
import NoteEditor from "./NoteEditor.vue";
export default {
  name: "notecontainer",
  components: {
    NoteSelector,
    NoteEditor,
  },
};
</script>