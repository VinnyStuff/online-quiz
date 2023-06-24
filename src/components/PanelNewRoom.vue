<script setup>
</script>

<template>
    <div class="panel-new-room-container">
        <div class="forms-input">
            <p>Players</p>
            <v-select :items="amountPlayers" v-model="playerModel"></v-select>
        </div>
        <div class="forms-input">
            <p>Players</p>
            <v-select :items="amountPlayers" v-model="playerModel"></v-select>
        </div>
    </div>
</template>

<script>
export default {
    data: () => ({
      amountPlayers: ['1', '2', '3', '4', '5', '6'],
      playerModel: '6',
    }),
}
</script>   

<style scoped>
.panel-new-room-container {

}
.forms-input{
    display: flex;
    align-items: center;
    background-color: red;
}
</style>
