<script>
    import Logo from "../../src/lib/images/logo.png"

</script>


<style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

    body {
        display: flex;
        flex-direction: column;
        margin: 0;
        padding: 0;
        height: 100vh;
        width: 100vw;
        background-color: white;
        font-family: Poppins;
    }

    nav {
        display: flex;
        align-items: center;
        height: 6.5rem;
        border-bottom: 1px solid #DADADA;
        padding: 0 25rem;

    }

    nav img {
        height: 2.5rem;
    }

    main {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        height: 100%;
        text-align: center;

    }

    h1 {
        font-weight: 900;
        font-size: 5rem;
        margin: 0;
        padding: 0;
    }
    p {
        margin: 0;
    }

    footer {
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-between;
        background-color: black;
        height: 3.5rem;
        color: white;
        padding: 0 25rem;
        font-size: 0.75rem;
    }

    footer a {
        color: #50F592;
    }

    .t_gr {
        color: #50F592;
    }

    /** Mittelgroße Monitore: Inhalte in zwei Spalten **/
@media (max-width: 1400px) {
    h1 {
        font-size: 4rem;

    }

    footer {
        padding: 0 10rem;
    }

    nav {
        padding: 0 10rem;
    }
}

@media (max-width: 800px) {
    h1 {
        font-size: 3rem;

    }

    footer {
        padding: 1rem;
        flex-direction: column-reverse;
        align-items: flex-start;
    }

    nav {
        padding: 0 1rem;
    }
    main {
        padding: 0 1rem;
    }
}
</style>

<body>
    <nav>
        <img src={Logo} alt="Cashback Planet Logo">
    </nav>
    <main>
        <h1>BALD VERFÜGBAR<span class="t_gr">!</span></h1>
        <p>Aktuell passiert im Hintergrund noch einiges. </p>
        <p>Wir sind aber bald mit den besten Deals für dich da! </p>
    </main>
    <footer>
        <p>Copyright <span class="t_gr">©</span> 2024 cashbackplanet.de. All rights reserved.</p>
        <div>
            <a href="">Impressum</a>
        </div>
    </footer>

</body>