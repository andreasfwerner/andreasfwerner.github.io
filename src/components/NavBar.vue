<!---
#05386B
#379683
#5CDB95
#8EE4AF
#EDF5E1-->
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
        display: flex;
        box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
        

    }
    .filler{
        width: 30%;
        height: 100%;
        background-color:#379683;

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
        background-color:#379683;
    }
    p{
        font-size: 1.5em;
        font-family: 'Courier New', Courier, monospace;
        font-weight: bold;
        letter-spacing: .3rem;
        color: #05386B;
    }

</style>