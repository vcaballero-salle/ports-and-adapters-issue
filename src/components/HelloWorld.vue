<script>
import SayHello from "../model/SayHello.ts";

export default {
  data() {
    return {
      msg: SayHello.sayHello(),
    }
  },
}
</script>

<template>
  <h1>{{ msg }}</h1>

</template>

