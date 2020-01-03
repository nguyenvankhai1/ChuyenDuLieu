<template>
    <div class="cha">
        <ComCon v-model="value"></ComCon>

    </div>
</template>
<script>

import ComCon from './ComCon'

export default {
    name:'cha',
    data(){
        return{
            value:'GIỮ LIỂU CỦA COMPONENT CHA'
        }
    },

    components: {
       ComCon
    }
    
    }

</script>
<style scoped>
       
</style>