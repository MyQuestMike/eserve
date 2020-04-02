<template>
    <div id='home' class="home">
        <!--App header starts here -->
        <AppHeader />
        <!--App header ends here -->
                
        <!--App Navigation starts here -->
        <AppNavbar />
        
        <!--App Navigation ends here -->
        
        <!--App Video Section starts here -->
        <AppVideo />

        <!-- Video Section ends here -->

        <!-- Slides Section starts here -->
        <AppSlides />
        <!-- Slides Section ends here -->

        <!-- Books Section starts here -->
        <AppBooks />
        <!-- Books Section starts here -->

        <!-- Cheatsheets Section starts here -->
        <AppCheatsheets />
        
        <!-- CheatSheets Section ends here -->

        <!--Footer Section starts here -->
        <AppFooter />
        <!--App Footer section ends here -->
    </div>
</template>

<script lang='ts'>
    import AppHeader from "./AppHeader.vue";
    import AppNavbar from "./AppNavbar.vue";
    import AppSlides from "./AppSlides.vue";
    import AppFooter from "./AppFooter.vue";
    import AppVideo from "./AppVideo.vue";
    import AppBooks from "./AppBooks.vue";
    import AppCheatsheets from "./AppCheatsheets.vue"
    export default {
        name: 'Home',
        components: {
            AppHeader,
            AppNavbar,
            AppSlides,
            AppFooter,
            AppVideo,
            AppBooks,
            AppCheatsheets
        }
    }
    
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.container {
    margin-bottom: 10px;
}
.app-heading {
    padding-top: 20px;
    color: purple;
    text-align: left;
}
.app-header {
    width: 100%;
    height: 60px;
    padding-top: 10px;
    background-color: purple;;
    color: #fff;
}
.app-header-heading {
    font-size: 2rem;
}

.bg {
    background-color: sienna;
}

.navi ul {
    display: flex;
    list-style: none;
    justify-content: center;
}
.navi ul li {
    padding-right: 2rem;
}
.navi ul li a {
    text-decoration: none;
    color: purple;;
    line-height: 65px;
    font-size: 2rem;
}
.navi ul li a:hover {
    color: seagreen;
}
.navbar-toggler {
    background: purple !important;
}
button.navbar-toggler span{
   background: rgb(104, 10, 104);   
}
.navbar-toggler-icon{
    background:rgb(139, 156, 139);
}
.collapse{
    background-color: rgb(90, 38, 143, 0.2);
}
.bottom-clear {
    margin-bottom: 10px;
}

.card {
    margin-bottom: 5px;
}

.btn {
    color: seagreen;
}
.footer
.footer h3{
  text-align: center;
}
</style>