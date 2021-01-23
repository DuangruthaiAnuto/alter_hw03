<template>
  <div>
    <div class="student-list">
      <h1>{{ student.studentId }}</h1>

      <div style="width: 100%; text-align: left">
        <img
          style="float: left; padding: 10px"
          width="155px" height="206px"
          v-bind:src="student.picture"
        />
        <div style="padding:10px;">
          <b>ชื่อ:</b>{{ student.FirstName }}<br />
          <b>นามสกุล:</b>{{ student.LastName }}<br />
          <b>น้ำหนัก:</b>{{ student.weight }}<br />
          <b>ส่วนสูง:</b>{{ student.height }}
        </div>
      </div>
      <br />
    </div>
  </div>
</template>

<script>
export default {
  name: "StudentList",
  components: {},
  props: ["student"],
};
</script>



<style>
.student-list{
  background: #f4f4f4;
  padding: 80px;
  height: 300px;
  width: 400px;
  margin: 50px;
}
</style>