<header>
    <h1>The substance</h1>
</header>
<main>
<slot/>
</main>
<footer>
    And people always ask for something new.
Renewal is inevitable
</footer>

<style>
    header{
        padding: 1rem;
        border-radius: 1.5rem;
        border: solid;
    }

    main{
        display: flex;
        flex-flow: column;
        gap: 0.5rem;
    }

    footer{
        font-weight: bold;
        width: 100%;
        display: flex;
        justify-content: end;
    }
</style>