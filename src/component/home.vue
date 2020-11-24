
<template>
  <div class="container">

              <form class="form-horizontal">
                <fieldset>
                  <legend>Spotify Music</legend>
                  <app-search></app-search>

                </fieldset>
              </form>

        <div class="row">
              <div class="col-md-12">
                <app-result></app-result>
              </div>
        </div>
  </div>
</template>

<script>
import SearchArea from './SearchArea.vue'
import ResultArea from './ResultArea.vue'

export default{
  components:{
    'app-search':SearchArea,
    'app-result':ResultArea,
  }
}
</script>

<style >

</style>
