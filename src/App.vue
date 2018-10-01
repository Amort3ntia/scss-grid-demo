<template>
    <div id="app">
        <header class="header">
            <span class="logo">
                LOGO
            </span>
            <a href="something" class="button1">Login</a>
            <a href="something" class="button1">Create Account</a>
        </header>
        <section class="wrapper">
            <div class="row">
                <div class="col-12">
                    <b>Main content width: 1200px</b>
                </div>
            </div>
            <div class="row">
                <div class="col-4">
                    Three Rings for the Elven-kings under the sky, <br>
                    Seven for the Dwarf-lords in halls of stone, <br>
                    Nine for Mortal Men, doomed to die, <br>
                </div>
                <div class="col-4">
                    One for the Dark Lord on his dark throne <br>
                    In the Land of Mordor where the Shadows lie. <br>
                </div>
                <div class="col-4">
                    One Ring to rule them all, One Ring to find them, <br>
                    One Ring to bring them all and in the darkness bind them. <br>
                </div>
            </div>
        </section>
        <footer class="footer">Bottom Nav</footer>
    </div>
</template>

<script>

  export default {
    name: 'app',
    components: {}
  }
</script>

<style lang="scss">
    @import "grid";

    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        background-color: #cba550;
    }

    .logo {
        float: left;
        padding: .5em;
    }

    .header {
        text-align: right;
        padding: .6em;
        background: #B2B2B2;
    }

    .wrapper {
        padding: 30px;
        text-align: left;
        background: #FFCCCC;
        display: grid;
    }

    .footer {
        padding: 20px;
        background: #B2B2B2;
        text-align: center;
    }

    a.button1 {
        display: inline-block;
        padding: 0.35em 1.2em;
        border: 0.1em solid #FFFFFF;
        margin: 0 0.5em 0.1em 0;
        border-radius: 0.12em;
        box-sizing: border-box;
        text-decoration: none;
        font-family: 'Roboto', sans-serif;
        font-weight: 300;
        color: #FFFFFF;
        text-align: center;
        transition: all 0.2s;
    }

    a.button1:hover {
        color: #000000;
        background-color: #FFFFFF;
    }

    @media all and (max-width: 30em) {
         a.button1 {
            display: block;
            margin: 0.4em auto;
        }
    }
</style>
