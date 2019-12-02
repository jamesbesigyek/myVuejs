<template>
    <div >
        <div class='container-fluid'>
            <div class="row">
                <div class="col-xl-12">
                    <NavBar/>
                </div>
            </div>
            <div class="row">
                <div class="col-sm-3">
                     <Sidebar/>
                </div>
                <div class="col-sm-6">
                     <button type="button" class="btn btn-primary">center</button>
                </div>
                <div class="col-sm-3">
                     <button type="button" class="btn btn-primary">right</button>
                </div>
                
            </div>
            <div class="row">
                <div class="footer col-sm-12">
                    <AppFooter />
                </div>
                
            </div>
        
            

        </div>
        
    </div>  
</template>
<script>
    import Sidebar from "./Sidebar.vue"
    import NavBar from "./NavBar.vue"
    import AppFooter from "./AppFooter.vue"
    export default {
        name: "AppBodyStructure",
        components:{ 
            Sidebar,NavBar,AppFooter
        }
    }
</script>
<style>
.btn{
    width: 100%;
    height: 500px;
}
    
</style>