<template>
    <div class="hello">
        <div class="headBox">
            <div class="headLine">Hallo</div>
            <div>
                <b-button class="roomButton" variant="outline-light">Mein Raum</b-button>
            </div>
            <div class="roomBoxes">
            <div class="roomBox" id="box1"></div>
            <div class="roomBox" id="box2"></div>
        </div>
        <div class="roomBoxesRow">
            <div class="roomBox" id="box3"></div>
            <div class="roomBox" id="box4"></div>
        </div>
        <div class="roomBoxesRow">
            <div class="roomBox" id="box5"></div>
            <div class="roomBox" id="box6"></div>
        </div>
        </div>
        
    </div>
</template>

<script>
    export default {
        name: 'startscreen',
        props: {
            msg: String
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{
    height: 100vh;
    background-color: #C0C5CD;
}
    .headBox {
        height: 40vh;
        width: 100vw;
        background-color: #677792;
        border-bottom-right-radius: 5%;
        border-bottom-left-radius: 5%;
    }

    .headLine {
        padding: 5vh;
        padding-top: 8vh;
        padding-bottom: 2vh;
        color: #ffffff;
        font-size: 40px;
        font-family: 'Source Sans Pro', sans-serif;
        font-weight: bolder;
    }

    .roomButton {
        height: 6vh;
        width: 90vw;
        padding: 0.5vw;
        margin: 5vw;
        border: 2px solid #ffffff;
        border-radius: 20px;
    }
    .roomBoxes{
        display: flex;
        flex-direction: row;
    }
    .roomBoxesRow{
        display: flex;
        flex-direction: row;
    }
    .roomBox{
        height: 20vh;
        width: 100vw;
        background-color: #ffffff;
        border: 2px solid #81B9BF;
        border-radius: 20px;
        padding: 1vw;
        margin: 2vw;
    }
</style>