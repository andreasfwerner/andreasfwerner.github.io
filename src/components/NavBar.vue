<template>
    <div class="navbar">
        <div class="filler">
            <p>andreasfwerner</p>
        </div>
        <div class="flexwrap">
            <NavBarButton></NavBarButton>
            <NavBarButton></NavBarButton>
            <NavBarButton></NavBarButton>
            <NavBarButton></NavBarButton>
        </div>
    </div>
</template>

<script>
import NavBarButton from './NavBarButton.vue'
export default{
    name: 'NavBar',
    components: {
        NavBarButton
  }
}
</script>

<style>
    *{
        margin:0;
        padding:0;

    }
    .navbar{
        width: 100%;
        height: 7em;
        background-color: green;
        display: flex;

    }
    .filler{
        width: 30%;
        height: 100%;
        background-color: aqua;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .flexwrap{
        display: flex;
        flex-direction: row;
        justify-content: space-evenly;
        align-items: center;
        width: 70%;
        height: 100%;
        background-color: aliceblue;
    }
    p{
        font-size: large;
        font-family: 'Courier New', Courier, monospace;
        font-weight: bold;
    }

</style>