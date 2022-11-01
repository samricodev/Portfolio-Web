<style>
    .Header{
        background-color: #fff;
        color: #000;
        width: 100%;
        height: auto;
    }

    .Header nav {
        padding: 2px 10px 2px 10px;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
    }

    .Logo{
        text-decoration: none;
        color: #000;
    }

    .Logo:hover{
        color: green;
    }

    .Header nav ul{
        list-style: none;
        display: flex;
        flex-direction: row;
    }

    .Header nav ul li{
        margin-left: 5px;
    }

    .Header nav ul li a{
        text-decoration: none;
        color: #000;
        font-size: 1.05rem;
        font-weight: bold;
    }

    .Header nav ul li a:hover{
        border-bottom: 4px solid rgb(27, 117, 24);
    }
</style>

<div class="Header">
    <header>
        <nav>
            <!-- svelte-ignore a11y-invalid-attribute -->
            <a href="#" class="Logo"><h2>SamRico</h2></a>
            <ul>
                <!-- svelte-ignore a11y-invalid-attribute -->
                <li><a href="#">Portafolio</a></li>
                <!-- svelte-ignore a11y-invalid-attribute -->
                <li><a href="#">Acerca</a></li>
                <!-- svelte-ignore a11y-invalid-attribute -->
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
    </header>
</div>