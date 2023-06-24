<template>
    <v-card class="card">
        <v-icon class="class-icon" icon="mdi-google-classroom" size="35px"></v-icon>

        <div class="class-title-container"> 
            <v-card-title class="class-title">Lorem ipsum dolor sit amet.</v-card-title>
        </div>

        <div class="players-container">
            <v-icon class="player-icon" icon="mdi-account-outline" size="large"></v-icon>
            <v-card-subtitle class="amount-players">0/6</v-card-subtitle>
        </div>
    </v-card>
</template>

<script>
export default {
    props: {
        icon: String,
        title: String,
        players: Number,
        playersLimit: Number,
    },
}
</script>   

<style scoped>
.card{
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 10px 15px;
}
.class-icon{
    padding: 20px;
}
.class-title-container{
    flex-grow: 1;
    text-overflow: ellipsis;
    overflow: hidden;
    white-space: nowrap; 
}
.class-title{
    padding: 0 14px;
}
.players-container{
    margin-left: auto;
    display: flex;
    align-items: center;
}
.amount-players{
    padding: 0;
    margin-left: 5px;
    font-weight: 700;
}
</style>
