<template>
    <div>

<h1>about me</h1>

    </div>
</template>

<script>
export default {
data(){
return{
jokes:[]
}
},

created(){
const config={
header:{
'Accept':'applicatipn/json'

}

}

},

    head(){
return{

    title:"about the app",
    meta:[{
hid:"description",
name : "description",
content: "nothing about me"
}
    ]
}


    }

}
</script>

<style>

</style>
