<template>
    <div class="hello">
        <div class="headBox">
            <div class="">
            <b-button size="lg" variant="primary" class="backButton">
                <b-icon icon="arrow-left-circle-fill" variant="light" aria-label="Help"></b-icon>
            </b-button>
            </div>
            <div class="headLine">Raum H 2.16</div>
            <div>
                <div class="subheading">Seminarraum</div>
            </div>
            <div class="spacing"></div>
            <b-button-group class="buttonSwitch">
                <b-button id="button1">Button 1</b-button>
                <b-button id="button2">Button 2</b-button>
                <b-button id="button3">Button 3</b-button>
            </b-button-group>
            <div class="spacing"></div>
            <div class="co2info"></div>


        </div>

    </div>
</template>

<script>
    export default {
        name: 'roomdetail',
        props: {
            msg: String
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .hello {
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
        padding-bottom: 0vh;
        color: #ffffff;
        font-size: 40px;
        font-family: 'Source Sans Pro', sans-serif;
        font-weight: 700;
    }

    .subheading {
        padding: 5vh;
        padding-top: 0vh;
        padding-bottom: 1vh;
        color: #ffffff;
        font-size: 24px;
        font-family: 'Source Sans Pro', sans-serif;
        font-weight: 100;
    }

    .co2info {
        height: 45vh;
        width: 95vw;
        background-color: #ffffff;
        border-radius: 20px;
        padding: 1vw;
        padding-top: 5vh;
        margin-top: 5vh;
        margin: 2vw;
    }

    .spacing {
        height: 3vh;
    }

    .buttonSwitch {
        padding: 1vw;
        padding-top: 0vh;
        margin-top: 0vh;
        margin: 2vw;
        margin-bottom: 0vh;
        padding-bottom: 0vh;
        width: 95vw;
    }

    #button1 {
        border-top-left-radius: 20px;
        border-bottom-left-radius: 20px;
        background-color: #81B9BF;
        border-color: #81B9BF;
        font-weight: bolder;
    }

    #button2 {
        background-color: #ffffff;
        border-color: #ffffff;
        color: #677792;
        font-weight: bolder;
    }

    #button3 {
        border-top-right-radius: 20px;
        border-bottom-right-radius: 20px;
        background-color: #ffffff;
        border-color: #ffffff;
        color: #677792;
        font-weight: bolder;
    }
    .backButton{
        height: 10vh;
        font-weight: 10vw;
        background-color: transparent;
        border-color: transparent;
    }
    .iconButton{
        color: black;
    }
</style>