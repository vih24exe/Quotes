<template>
    <div class="container">
        <app-header :quoteCount="quotes.lenght" maxQuotes=10>
        </app-header>
            
    </div>
</template>

<script>
    import Header from './components/Header.vue'
    export default {

        components: {
            appHeader: Header
        },

        data: function(){
            return{
                quotes:[ 
                    'Hola mundo cruel',
                ],
                maxQuotes: 10
            }
        }
        
    }
</script>

<style>
</style>
