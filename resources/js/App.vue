<template>
  <router-view></router-view>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700&display=swap");

html {
  font-family: "Poppins", sans-serif;
}
body {
  background-color: #f5f5f5;
}
html::-webkit-scrollbar {
  width: 8px;
}
html::-webkit-scrollbar-thumb {
  background: #ccc;
  border-radius: 4px;
}
html::-webkit-scrollbar-thumb:active {
  background-color: #999999;
}
html::-webkit-scrollbar-thumb:hover {
  background: #b3b3b3;
  box-shadow: 0 0 2px 1px rgba(0, 0, 0, 0.2);
}
html::-webkit-scrollbar-track {
  background: #e1e1e1;
  border-radius: 4px;
}
html::-webkit-scrollbar-track:hover,
html::-webkit-scrollbar-track:active {
  background: #d4d4d4;
}
</style>
