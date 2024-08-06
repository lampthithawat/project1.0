<template>
  <div class="mx-6 my-10">
    <v-row class="mb-4">
      <v-col>
        <v-btn class="mr-2" color="blue">
          เพิ่ม Part
        </v-btn>
        <v-btn class="mr-2" color="green">
          Import
        </v-btn>
        <v-btn class="mr-2" color="orange">
          Export
        </v-btn>
      </v-col>
    </v-row>
    
    <v-data-table
      :headers="headers"
      class="elevation-1"
    />
  </div>
</template>

<script>
export default {
  name: 'MainComponent',
  props: {
    msg: String
  },
  data: () => ({
    headers: [
      {
        text: "Part No",
        value: "Part",
      }
    ]
  })
}
</script>