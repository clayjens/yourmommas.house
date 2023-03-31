<script lang='ts'>
	// The ordering of these imports is critical to your app working properly
	import '@skeletonlabs/skeleton/themes/theme-crimson.css';
	// If you have source.organizeImports set to true in VSCode, then it will auto change this ordering
	import '@skeletonlabs/skeleton/styles/all.css';
	// Most of your app wide CSS should be put in this file
	import '../app.postcss';

	import * as S from '@skeletonlabs/skeleton';
	import { GithubIcon, LinkedinIcon, TwitterIcon } from "svelte-feather-icons";

	const year = new Date().getFullYear();
</script>

<S.AppShell>
	<svelte:fragment slot="header">
		<S.AppBar>
			<a class="btn variant-ghost" href="/">CJ</a>
			<a class="btn variant-ghost" href="/experience">Experience</a>
		</S.AppBar>
	</svelte:fragment>
	<div class="container h-full mx-auto flex justify-center items-center">
		<slot />
	</div>
	<svelte:fragment slot="footer">
		<footer class="footer p-2 flex justify-between">
			<div>
				<a class="btn btn-sm variant-ghost" href="https://github.com/clayjens">
					<GithubIcon/>
				</a>
				<a class="btn btn-sm variant-ghost" href="https://www.linkedin.com/in/clayton-jensen-875556219/">
					<LinkedinIcon/>
				</a>
				<a class="btn btn-sm variant-ghost" href="/" on:click={() => alert("My Twitter isn't linked, maybe one day!")}>
					<TwitterIcon/>
				</a>
			</div>
			<div>
				<span>Clayton Jensen &copy; {year}</span>
			</div>
		</footer>
	</svelte:fragment>
</S.AppShell>