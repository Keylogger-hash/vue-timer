<script setup lang="ts">

import { reactive, computed } from 'vue';

</script>

<template>
<div class="Timer">
  <div class="Timer-header">
    Timer
  </div>
  <div class="Timer-Form">
    <div class="Timer-Input-Wraps">
      <div class="Timer-Input">
        <input aria-invalid="false" autocomplete="off" placeholder="00" max="59" min="0" inputmode="numeric" type="number"/>
      </div>
      <div class="Timer-Input">
        <input aria-invalid="false" autocomplete="off" placeholder="00" max="59" min="0" inputmode="numeric" type="number"/>
      </div>
      <div class="Timer-Input">
        <input aria-invalid="false" autocomplete="off" placeholder="00" max="59" min="0" inputmode="numeric" type="number"/>
      </div>
    </div>
    <div class="Timer-button">
      <button>
        Запустить
      </button>
    </div>
  </div>
</div>
</template>

<style scoped>
.Timer{
  display: flex;
  flex-direction: column;
  padding-bottom: 12px;
  background-color: #000;
  color:rgba(255,255,255);
  max-width:640px;
  font-size:18px;
  border-radius: 12px;
  margin-bottom: 10px;
  padding-bottom: 12px;
  padding-left: 16px;
  padding-right: 16px;
  padding-top: 12px;
}
.Timer-header{
  display: flex;
  align-items: flex-start;
  font-weight: 700;
  font-size: 18px;
}
.Timer-Form{
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.Timer-button button{
  background-color:#fc0;
  color:#000000;
  border-radius: 12px;
  font-size: 18px;
  outline: none;
  border: none;
  text-align: center;
  padding-left:12px;
  padding-right: 12px;
}
.Timer-Input-Wraps{
  display: flex;
  flex-direction: row;
}
.Timer-Input{
  margin:0 8px;
}
.Timer-Input input{
  background: 0 0;
  border:none;

  margin: 0;
  outline: 0;
  color: rgba(255,255,255,.75);
  font-size: 60px;
}

</style>
