<script lang="ts">
    import { DownloadCloudIcon, MailIcon } from "svelte-feather-icons";

    let years_programming = new Date().getFullYear() - 2018;
</script>

<div class="space-y-4">
    <h1>My Experience</h1>
    <hr />
    <h2>Clayton Jensen</h2>
    <h3>Full-Time Student</h3>
    <p>
        I am a motivated student working towards degrees in Computer Science & Information Technology with a minor in Mathematics and a certificate in programming.

        I am contributing to Machine Learning-based research and developing my skills in producing Artificial Intelligence models.

        I am a skilled programmer with {years_programming} years of experience in software development, primarily in the C++ and Rust programming languages.
        I also have experience with developing websites.
    </p>
    <div class="space-x-2">
        <a class="btn variant-filled" href="./Clayton_Jensen__Resume.pdf" download="resume-Clayton_Jensen.pdf">
            <DownloadCloudIcon />
            <span>Download Clayton's Resume</span>
        </a>
        <a class="btn variant-filled" href="mailto:clayton.jensen@yourmommas.house">
            <MailIcon />
            <span>Send An Email</span>
        </a>
    </div>
</div>