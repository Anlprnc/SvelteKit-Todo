<div class="mainContainer">
    <slot/>
</div>

<style>
    .mainContainer {
        min-height: 100vh;
        background: linear-gradient(to right, #000000, #353535);
        color: white;
        position: relative;
        display: flex;
        flex-direction: column;
    }
</style>