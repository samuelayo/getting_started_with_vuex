<template>
  <div id="app"> 
    <div class="container">
    <div class="row">
        <div class="col-md-6">
            <hello></hello>
        </div>
        <div class="col-md-6">
           <done></done>
        </div>
    </div>
</div>
  </div>
</template>

<script>
import Hello from './components/Hello'
import Done from './components/Done'

export default {
  name: 'app',
  components: {
    Hello,
    Done
  }
}
</script>

