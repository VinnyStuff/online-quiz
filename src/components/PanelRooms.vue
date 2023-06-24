<script setup>
import Room from './Room.vue'
import PanelNewRoom from './PanelNewRoom.vue'
</script>

<template>
    <div class="panel-container">
        <div class="rooms-container">
            <Room/>
        </div>
        <div class="new-room-container">
            <PanelNewRoom/>
        </div>
    </div>
</template>

<script>

</script>   

<style scoped>
.panel-container{
    width: 100vw;
    max-width: 1000px;
    height: 90vh;
    background-color: grey;
    position: absolute;
    top: 50%;
    left: 50%;
    -ms-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
}
</style>
