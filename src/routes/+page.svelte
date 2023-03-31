<script lang="ts">
	import { GithubIcon, LinkedinIcon, TwitterIcon } from "svelte-feather-icons";
</script>

<svelte:head>
	<title>Clayton Jensen</title>
</svelte:head>

<div class="space-y-5">
	<h1>Hi, I'm Clayton</h1>
	<h3>I'm a Computer Science major focusing in software engineering and machine learning.</h3>
	<p>Currently, this website is a placeholder for more to come...</p>
	<hr />
	<h4>Why not check out my socials?</h4>
	<div class="space-x-2">
		<a class="btn variant-filled" href="https://github.com/clayjens">
			<GithubIcon/>
			<span>GitHub</span>
		</a>
		<a class="btn variant-filled" href="https://www.linkedin.com/in/clayton-jensen-875556219/">
			<LinkedinIcon/>
			<span>LinkedIn</span>
		</a>
		<a class="btn variant-filled" href="/" on:click={() => alert("My Twitter isn't linked, maybe one day!")}>
			<TwitterIcon/>
			<span>Twitter</span>
		</a>
	</div>
	<hr />
	<h4>Why is it called Your Momma's House?</h4>
	<p>It's a long story, but essentially I thought it was funny and provocative.</p>
	<p>Also, yourmommas.house is linked to a Google Workspace, so I can use funny email names like <a href="mailto:clayton.jensen@yourmommas.house">clayton.jensen@yourmommas.house</a>. Go ahead and send me an email!</p>
</div>
