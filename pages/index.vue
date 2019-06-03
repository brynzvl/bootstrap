<template>
    <div>
      <div class="jumbotron">
  
        <h1 class="display-3">What is Vue.js?</h1>
        <p class="lead">Vue <strong>(pronounced /vjuː/, like view) </strong>is a progressive framework for building user interfaces. Unlike other monolithic frameworks, Vue is designed from the ground up to be incrementally adoptable. The core library is focused on the
          view layer only, and is easy to pick up and integrate with other libraries or existing projects.</p>
        <p><a class="btn btn-lg btn-success" id="btn-success" href="https://vuejs.org/" role="button" data-toggle="tooltip" data-placement="bottom" title="www.vuejs.org">Get Started</a></p>
  
      </div>
      <div class="row marketing">
        <div class="col-lg-6">
          <h4>Approachable</h4>
          <p class="text-muted">Already know HTML, CSS and JavaScript? Read the guide and start building things in no time!</p>
  
          <h4>Versatile</h4>
          <p class="text-muted">An incrementally adoptable ecosystem that scales between a library and a full-featured framework.</p>
  
          <h4>Performant</h4>
          <p class="text-muted">20KB min+gzip Runtime, Blazing Fast Virtual DOM and Minimal Optimization Efforts
          </p>
        </div>
  
        <div class="col-lg-6">
          <h4>Approachable</h4>
          <p class="text-muted">Already know HTML, CSS and JavaScript? Read the guide and start building things in no time!</p>
  
          <h4>Versatile</h4>
          <p class="text-muted">An incrementally adoptable ecosystem that scales between a library and a full-featured framework.</p>
  
          <h4>Performant</h4>
          <p class="text-muted">20KB min+gzip Runtime, Blazing Fast Virtual DOM and Minimal Optimization Efforts
          </p>
        </div>
        
    </div>
     </div>

</template>

<script>
  import Logo from '~/components/Logo.vue'
  
  export default {
    components: {
      Logo
    }
  }
</script>
