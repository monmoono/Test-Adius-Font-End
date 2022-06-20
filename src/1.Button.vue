<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from '@/components/HelloWorld.vue'
</script>

<template>
  <header>
    <div>
          <button type="button" class="btn primary">Primary</button>
          <button type="button" class="btn secondary">Secondary</button>
          <button type="button" class="btn success">Success</button>
          <button type="button" class="btn danger">Danger</button>
          <button type="button" class="btn warning">Warning</button>
          <button type="button" class="btn info">Info</button>
          <button type="button" class="btn light">Light</button>
          <button type="button" class="btn dark">Dark</button>
          <button type="button" class="link">Link</button>
      </div>
  </header>
</template>

<style>
.btn {
  border: none;
  padding: 16px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
  border-radius: 8px;
  
}
.primary:focus , .secondary:focus ,.success:focus,.warning:focus, .danger:focus ,.info:focus,.light:focus ,.dark:focus{
   border-radius: 25px;
}
  .primary{
    background-color: #007bff;
    color: #fff;
  }

  .primary:hover {
    background-color:#0000FF;
    color: #fff;
}


.secondary{
    background-color: #6c757d;
    color: #fff;
  }

  .secondary:hover {
    background-color:#454b50;
    color: #fff;
}


.success{
    background-color: #0a9634;
    color: #fff;
  }

  .success:hover {
    background-color:#03551b;
    color: #fff;
}
 
.danger{
    background-color: #96130a;
    color: #fff;
  }

  .danger:hover {
    background-color:#5e0505;
    color: #fff;
}


.warning{
    background-color: #c4660f;
    color: #fff;
  }

  .warning:hover {
    background-color:#9e4a06;
    color: #fff;
}

.info{
    background-color: #078da5;
    color: #fff;
  }

  .info:hover {
    background-color:#077768;
    color: #fff;
}

.light{
    background-color: #fff;
    color: black;
  }

  .light:hover {
    background-color:#dbe2e1;
    color: black;
}

.dark{
    background-color: #000607bb;
    color: #fff;
  }

  .dark:hover {
    background-color:#000000;
    color: #fff;
}

.link{
  border: none;
  padding: 16px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
  border-radius: 8px;
}

.link:hover,.link:focus {
  color: #0000FF;
  text-decoration: underline;
}
  
</style>
