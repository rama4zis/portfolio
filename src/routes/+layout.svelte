<script>
  let { children } = $props();
  import "../app.css";
</script>

<div
  class="min-h-screen bg-gradient-to-t from-gray-700 via-gray-900 to-black"
>
  {@render children()}
</div>
