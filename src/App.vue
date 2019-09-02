<template>
  <a-form class="createleft" :form="form">
    <a-form-item label="文本信息">
      <a-input v-decorator="[
      'username'
      ]" />
    </a-form-item>
  </a-form>
</template>

<script lang="ts">
import { Vue, Component } from "vue-property-decorator";
@Component({})
export default class demo extends Vue {
  form = this.$form.createForm(this);
}
</script>