<script lang="ts">
import "./layout.css";
let { children } = $props();
</script>
<main class="min-h-screen w-screen flex flex-row font-display justify-center">
<article class="m-y-1 prose prose-slate dark:prose-invert justify-center w-5/6 p-4 bg-blend-color bg-[#77777777]">
   {@render children()}
</article>
</main>