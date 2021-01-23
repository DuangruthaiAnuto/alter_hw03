<template>
  <div id="app">
    <Students v-bind:student1="students" />
  </div>
</template>

<script>
import Students from "./components/Students.vue";

export default {
  name: "App",
  components: {
    Students,
  },
  data() {
    return {
      students: [
        {
          studentId: "614234005",
          FirstName: "นางสาวดวงฤทัย",
          LastName: "อนุโต",
          weight: 63,
          height: 160,
          picture:
            "https://raw.githubusercontent.com/DuangruthaiAnuto/Pic/main/1.jpg",
        },
        {
          studentId: "614234006",
          FirstName: "นางสาวสีนีนาถ",
          LastName: "สงเสน",
          weight: 52,
          height: 153,
          picture:
            "https://raw.githubusercontent.com/DuangruthaiAnuto/Pic/main/4.jpg",
        },
        {
          studentId: "614234012",
          FirstName: "นางสาวนัฐศภัทร",
          LastName: "สถิรเมธากร",
          weight: 63,
          height: 162,
          picture:
            "https://raw.githubusercontent.com/DuangruthaiAnuto/Pic/main/3.jpg",
        },
        {
          studentId: "614234013",
          FirstName: "นางสาวปริยาภัทร",
          LastName: "เจริญฤทธิ์",
          weight: 66,
          height: 162,
          picture:
            "https://raw.githubusercontent.com/DuangruthaiAnuto/Pic/3afa0339e9100f31ccc4fe600b9d51c1a40415b5/2.jpg",
        },
        {
          studentId: "614234021",
          FirstName: "นางสาวอรวรรณ",
          LastName: "หนูพลิก",
          weight: 68,
          height: 160,
          picture:"https://raw.githubusercontent.com/DuangruthaiAnuto/Pic/main/5.jpg",
        }
      ],
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
