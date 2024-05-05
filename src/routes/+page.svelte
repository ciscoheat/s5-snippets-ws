<script lang="ts"></script>

<!-- Remove the whitespace before the colon to remove error -->
{#snippet foo(test : string[])}
	<button>{test.join(", ")}</button>
{/snippet}
{@render foo(["a", "b"])}
