<template>
  <select @change="onChange()" v-model="selected" class="form-select mt-10 block w-full border p-3 rounded">
      
      <option value="0">Select Country</option>
      <option v-for="element in countries" :value="element.ID" :key="element">
          {{ element.Country }}
      </option>
  </select>
</template>

<script>
export default {
    name: 'CountrySelect',
    props: ['countries'],
    data() {
        return {
            selected: 0,
        }
    },
    methods: {
        onChange() {
            //
        }
    }

}
</script>

<style>

</style>