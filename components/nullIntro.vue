<template>
  <div class>
    <div class="my-12">
      <div class="typewriter mx-auto">
      <div class="typewriter-text">
        <h1 class="display-3 font-weight-bold">Welcome to null</h1>
      </div>
      </div>
      <v-container>
        <v-row>
          <v-col cols="12" md="10">
            <span class="headline">
              India's largest open security community.
              <br/>
              Registered as
              non-profit society in 2010.
              <br />
            </span>
          </v-col>
        </v-row>
      </v-container>
      
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.typewriter {
    font-family: Courier, monospace;
	display: inline-block;
}
.typewriter-text {
    display: inline-block;
  	overflow: hidden;
  	letter-spacing: 2px;
 	animation: typing 3s steps(30, end), blink .75s step-end infinite;
    white-space: nowrap;
    font-size: 30px;
    font-weight: 700;
    border-right: 4px solid lightgreen;
    box-sizing: border-box;
}

@keyframes typing {
    from { 
        width: 0% 
    }
    to { 
        width: 100% 
    }
}

@keyframes blink {
    from, to { 
        border-color: transparent 
    }
    50% { 
        border-color: orange; 
    }
}

</style>
