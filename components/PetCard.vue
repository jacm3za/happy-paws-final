<script setup lang="ts">
  import type { Pet } from '../types/pets'
  const { id, name, breed, image } = defineProps<Pet>()
</script>
