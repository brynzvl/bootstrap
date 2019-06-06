Vue.component('child', {
    props: ['text'],
    template: `<p>{{ text }}</p>`
  });
  new Vue({
    el: "#app",
    data() {
      return {
        message: 'Hello there!'
} }
});

<div id="app">
    <child :text="message"></child>
    <child :text="message"></child>
</div>