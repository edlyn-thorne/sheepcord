<script lang="ts">
import { base } from "$app/paths";
</script>

<svelte:head>
    <title>Days since Chat 1 fucked up.</title>
    <meta 
        name="description"
        content="It's been 0 days since Chat 1 fucked up."
    />
    <meta
        content="https://raw.githubusercontent.com/edlyn-thorne/sheepcord/main/static/embed.png"
        property="og:image"
    />
    <meta name="twitter:card" content="summary_large_image" />
</svelte:head>
<div class="wrapper" style="background-image: linear-gradient(rgba(0, 0, 0, 0.75), rgba(0, 0, 0, 0.9)), url('{base}/riifushi.png');">
    <div class="content">
        <span class="title">Days since <span class="chat-link"><a href="https://discord.com/channels/1207012737683689472/1207023404381904966">#⁠⟢☕chat-1</a></span> fucked up:</span>
        <br>
        <span class="counter">0</span>
    </div>
    <span class="footer">I HATE ALL OF YOU.</span>
</div>

<style lang="less">
:global(html, body) {
    margin: 0px;
    padding: 0px;
    border: none;
    outline: none;
    width: 100%;
    height: 100%;
}

.wrapper {
    width: 100%;
    height: 100%;
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
}

.content {
    font-family: 'Noto Sans';
    color: rgb(200, 200, 200);
    text-transform: uppercase;
    text-shadow: 0px 0px 50px black, 0px 0px 50px black;
    text-wrap: nowrap;
}

.title {
    font-size: 3rem;
    font-weight: 600;
}

@media (max-aspect-ratio: 1 / 1) {
    .title {
        font-size: 5vw;
    }
}

.chat-link {
    text-transform: none;
    background-color: #3d4270;
    text-shadow: none;
    font-family: Arial, Helvetica, sans-serif;
    padding: 5px;
    border-radius: 10px;
    transition: background-color 0.05s linear;
    color: white;
    &:hover {
        background-color: #5865f2;
    }
}

a {
    text-decoration: none;
    color: white;
}

.counter {
    font-weight: 1000;
    font-size: 25rem;
    display: block;
    text-align: center;
}

.footer {
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    bottom: 20px;
    font-family: Arial, Helvetica, sans-serif;
    color: rgb(200, 200, 200);
    font-weight: 600;
    font-size: 0.75rem;
}
</style>

