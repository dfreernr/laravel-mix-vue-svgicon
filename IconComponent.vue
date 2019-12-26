<template>  
    <span class="icon" v-html="require(`SVGPATH/${icon}.svg`)"></span>   
</template> 
<script>

export default {
    name: 'IconComponent',
    data() {
        return {
            
        }
    },
    props: {
        'icon': {
            type: String
        }
    }
}
</script>
