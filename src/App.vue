<template>
  <NavBar></NavBar>
    <div class="back">
      <p>
        AFW
      </p>
    </div>
    <div class="boxCont">
    <InfoBox>

    </InfoBox>
    </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import InfoBox from './components/InfoBox.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    InfoBox
  }
}
</script>

<style>
*{
  margin:0;
 padding: 0; 
}
html{
  background-color: #5CDB95;

}
body{
  min-height: 100%
}

.back p{
font-family: 'Varela Round';font-size: 48em;
-webkit-user-select: none; /* Safari */        
-moz-user-select: none; /* Firefox */
-ms-user-select: none; /* IE10+/Edge */
user-select: none; /* Standard */
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
  transform: rotate(25deg);
  opacity: 0.8;

}
.back{
  position: absolute;
  height: 90% ;
overflow: hidden;
}

.boxCont{
  width:100%;
  height: 100%;
  display:absolute;
  justify-content: center;
}




</style>
