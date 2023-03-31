<script lang="ts">
    import { DownloadCloudIcon, MailIcon } from "svelte-feather-icons";

    function handleDownload() {
        alert('Sadly this feature is not implemented yet :(')
    }
</script>

<div class="space-y-4">
    <h1>Lorem ipsum dolor sit amet</h1>
    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi delectus dolor eveniet, quasi in quisquam quam doloribus quia, fuga, sapiente molestiae natus exercitationem debitis numquam laudantium. Amet, sit optio! Nihil?
        Quaerat provident blanditiis unde porro, facere sed eaque dolore accusamus enim, ut eius dolorum ducimus veritatis laborum consectetur eos possimus? Odio quo optio neque nulla officia adipisci explicabo alias architecto.
    </p>
    <button class="btn variant-filled" on:click={handleDownload}>
        <DownloadCloudIcon />
        <span>Download Clayton's Resume</span>
    </button>
    <a class="btn variant-filled" href="mailto:clayton.jensen@yourmommas.house">
        <MailIcon />
        <span>Send An Email</span>
    </a>
</div>