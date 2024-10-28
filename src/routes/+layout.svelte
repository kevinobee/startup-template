<script>
	import '../app.css';
    import { ModeWatcher } from 'mode-watcher';
	/**
	 * @typedef {Object} Props
	 * @property {import('svelte').Snippet} [children]
	 */

	/** @type {Props} */
	let { children } = $props();
</script>
<ModeWatcher />

{@render children?.()}
