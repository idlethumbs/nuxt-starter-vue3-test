<template>
  <div class="homecard">
    <h2 style="padding: 10px; border-bottom: 1px solid #ccc">{{ $props.heading }}</h2>

    <div style="padding: 20px">
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam sit amet
        felis sit amet turpis lacinia hendrerit at ut leo. Morbi turpis lectus,
        condimentum sed tellus et, pulvinar pharetra nunc. Praesent sit amet
        diam suscipit, placerat velit eu, commodo nisi. Morbi magna orci,
        suscipit eu iaculis eget, malesuada non sem.
      </p>
      <button class="button">Button label</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeCard",
//  setup(props) {}
// Goals
// =============
// 1. Allow for a customised heading label
// 2. Allow Customised Button label that can be customised when using homecard component.
// 2. Add the ability to add a prefix fontawesome icon before the heading.
// 3. Allow overriding the default text content with any other output e.g images/other components.
// 5. React to a click on the Button in homecard from the parent component (App.vue)

};
</script>


 

<style lang="scss" scoped>
.homecard {
  border: 1px solid #ccc;
  margin: 20px;
  border-radius: 8px;
  background: #fff;
}

.button {
  font-family: arial;
  font-size: 16px;
  padding: 0.6em 1em;
  background-color: azure;
  border: 1px solid lightgray;
  border-radius: 8px;
  display: inline-flex;
}
</style>