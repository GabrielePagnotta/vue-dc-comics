<template>
        <div class="cardbox">
            <div>
                <div class="imagecontainer" >
                    <img :src="cards.thumb" alt="comix">
                </div>
                <div>
                    <h3>{{cards.series}}</h3>
                </div>
                
            </div>
            
            
        </div>
</template>

<script>

    export default {
        name:"CardContent",
        props:{
            cards: Object
        }
    }
</script>

<style lang="scss" scoped>
    

    .cardbox{
        display: flex;
        flex-direction: column;
        width: calc(100% /6 - 10px); 
        height:20%;
        justify-content: center;
        margin-top: 50px;
        
    }

    h3{
       padding:0 75px;
       color:white;
    }
    

   

    
    .imagecontainer{
        height: 300px;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        
        img{
            width: 60%;
            height:300px;
            object-fit:cover;
        }
        
    }

   
    
</style>