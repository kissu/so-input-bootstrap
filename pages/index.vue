<script>
export default {
  data() {
    return {
        showPassword: false
     }
  }
}
</script>

<template>
  <div>
    Nice input <b-form-input :type="showPassword ? 'text' : 'password'"></b-form-input>

    <button @click="showPassword = !showPassword">
      toggle it
    </button>
  </div>
</template>
