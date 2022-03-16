<template>
    <footer>
        <div class="container">
            <div class="1">
                <div class="logo">
                    <h3>Denov 4-son</h3>
                    <p>kasb hunar maktabi</p>
                </div>
                <div class="text">
                    <p>A small river named Duden flows by their place and supplies it with the necessary regelialia.</p>
                </div>
                <div class="socially">
                    <fa :icon=" ['fab', 'facebook'] "/>
                    <fa :icon=" ['fab', 'telegram'] "/>
                    <fa :icon=" ['fab', 'instagram'] "/>
                </div>
            </div>
        </div>
    </footer>   
</template>
<script>
export default {
  name: 'Footer'
}
</script>
<style scoped>
.socially {
    font-size: 25px;
}
</style>