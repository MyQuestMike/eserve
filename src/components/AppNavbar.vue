<template>
    <div class="container">
        <div class="row">
            <div class="col">
                <div class="container">
                    <nav class="navi navbar navbar-expand-lg">
                        <button class="navbar-toggler" 
                            type="button" 
                            data-toggle="collapse" 
                            data-target="#collapser" 
                            aria-controls="navbarNav" 
                            aria-expanded="false" 
                            aria-label="Toggle navigation">
                            <span class="navbar-toggler-icon"></span>
                        </button>
                        <div class="collapse navbar-collapse" id="collapser">
                            <ul class="navbar-nav">
                                <li class="nav-item active"><a class="nav-link" href="#">Home</a></li>
                                <li class="nav-item"><a class="nav-link" href="#">Books</a></li>
                                <li class="nav-item"><a class="nav-link" href="#">Slides</a></li>
                                <li class="nav-item"><a class="nav-link" href="#">Cheatsheets</a></li>
                            </ul>
                        </div>
					</nav>
                    
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "AppNavbar",
        
    }
    
</script>

<style scoped>

</style>