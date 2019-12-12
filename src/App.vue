<template>
  <div id="app">
    <transition>
      <router-view />
    </transition>
  </div>
</template>

<style>
  @import url('https://cdn.bootcss.com/font-awesome/4.7.0/css/font-awesome.css');

  html,
  body {
    padding: 0;
    margin: 0;
    background-color: #ffedff;
  }

  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    height: 100%;
    -webkit-user-select: none;
    -webkit-touch-callout: none;
    -webkit-tap-highlight-color: transparent;
  }
</style>
