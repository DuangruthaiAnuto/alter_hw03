<template>
  <div>
      <div v-bind:key="student.studentId" v-for="student in student1">
          <StudentList v-bind:student="student" />
      </div>

  </div>
</template>

<script>
import StudentList from './StudentList.vue'

export default {
    name: 'Students',
    components:{
        StudentList,
    },
    props:["student1"]
};
</script>

<style>
</style>