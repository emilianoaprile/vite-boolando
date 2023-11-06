<script>
export default {
    name: 'PageHeader',
    data() {
        return {

        }
    },
    methods: {

    }
}
</script>

<template>
    <div>
        <header class="page-header">
            <div class="container">
                <nav class="header-navbar">

                    <ul class="navbar-menu">
                        <li class="navbar-menu-items"><a href="#">Donna</a></li>
                        <li class="navbar-menu-items"><a href="#">Uomo</a></li>
                        <li class="navbar-menu-items"><a href="#">Bambino</a></li>
                    </ul>

                    <div class="header-logo">

                        LOGO

                    </div>

                    <ul class="navbar-icons">
                        <li class="navbar-icon-items"><a href="#">Utente</a></li>
                        <li class="navbar-icon-items"><a href="#">Preferiti</a></li>
                        <li class="navbar-icon-items"><a href="#">Carrello</a></li>
                    </ul>

                </nav>
            </div>
        </header>

    </div>
</template>

<style scoped>
.page-header {
    background-color: orange;
    padding: 20px;
}

.header-navbar {
    display: flex;
    justify-content: space-between;
}

.header-logo,
.navbar-menu,
.navbar-icons {
    display: flex;
    align-items: center;
}

.navbar-menu-items,
.navbar-icon-items {
    padding: 5px 10px;
}
</style>