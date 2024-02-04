<script lang="ts">
	import { page } from '$app/stores';
</script>


<h1>Yikes! 💥</h1>

<p>Something went horribly wrong</p>
<pre>{JSON.stringify($page, null, 2)}</pre>
