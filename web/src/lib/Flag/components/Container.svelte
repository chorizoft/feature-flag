<script>
  import { fade } from 'svelte/transition';
</script>

<li
  class="flex pl-2 py-3 my-3 text-xl bg-customGray border-black border-2 border-solid rounded-2xl"
  transition:fade
>
  <slot />
</li>
