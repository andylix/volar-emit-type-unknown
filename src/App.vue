<script lang="ts" setup>
import MyButton from './components/MyButton.vue'

function add(param: number) {
  console.log('add', param)
}

function foo(str: string) {
  console.log(str)
}

</script>

<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <MyButton
    @add-something="foo"
  ></MyButton>
</template>
