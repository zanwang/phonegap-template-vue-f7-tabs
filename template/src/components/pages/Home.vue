<template>
  <div>
    <!-- Scrollable page content-->
    <f7-block-title>{{ title }}</f7-block-title>
    <f7-block inner>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Distinctio
        est aliquam officiis quaerat placeat, cum explicabo magni soluta totam
        maxime autem minima accusamus eos suscipit dignissimos corporis modi
        voluptatum fugiat!
      </p>
    </f7-block>
  </div>
</template>

<script>
  export default {
    name: 'Home',
    data () {
      return {
        title: 'Home Page'
      };
    }
  };
</script>
