<template>
  <div>
    <add-student ></add-student>
    <student-list></student-list>
  </div>

</template>

<script>
import addStudent from '@/components/addStudent/add'
import studentList from '@/components/addStudent/studentList'
export default{
  components:{
    addStudent,
    studentList
  },
  data(){
    return {
      list : [],
    }
  },
  methods: {
    // add(name){
    //   this.list.push(name);
    // }
  }
}
</script>

<style scoped>

</style>
