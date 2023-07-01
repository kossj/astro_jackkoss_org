<script>
    let platforms = ['github', 'fortnite', 'instagram', 'linkedin', 'twitter', 'twitch', 'youtube'];
    let username = 'kossj';
</script>

{#each platforms as platform, i}
    <a href="https://{platform}.com/{username}">{platform}</a>{#if i < platforms.length - 1}&nbsp;{/if}
{/each}