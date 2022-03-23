<!-- src/routes/about.svelte -->
<svelte:head>
    <title>About</title>
</svelte:head>

<div class="main_container">
    <section>
        <div class="inner-container">
            <h2 class="about-title">I'm Claude Betz👋</h2>
            <div class="about-subtitle">
                <p>

                </p>
                <p>
                    Just trying to figure it all out. Reach out at
                    <span class="info-text">claude.betz47@gmail.com</span>
                </p>
            </div>
        </div>
    </section>
</div>

<style>
    .main_container {
        margin: 0 80px 0 65px;
    }

    .about-title {
        font-size: 4.2rem;
        font-weight: bold;
        margin-top: 11rem;
    }

    .about-subtitle {
        margin-top: -2rem;
    }

    .about-subtitle >p {
        width: 60%;
        font-weight: normal;
        font-size: 1rem;
        line-height: 2rem;
    }

    .info-text {
        font-style: italic;
        font-weight: bold;
    }
</style>