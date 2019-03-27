<template>
  <table id="table">
     <tr id="headers">
         <th> Last Name | </th>
         <th> First Name | </th>
         <th> Case File # | </th>
         <th> DA Supervisor | </th>
         <th> Date Filed | </th>
         <th> Probation Ends | </th>
         <th> Reference Result | </th>
         <th> Successful Contact? | </th>
         <th> Restitution/Fees/Fines | </th>
         <th> Failure to... | </th>
         <th> Notes: </th>
     </tr>
  </table>
</template>



<script>
const headings = [
    'Last Name',
    'First Name',
    'Case File #',
    'DA Supervisor',
    'Date Filed',
    'Probation Ends',
    'Reference Result',
    'Successful Contact?',
    'Restitution/Fees/Fines',
    'Failure to...',
    'Notes:'
];

export default {
  name: 'TableComponent'
}
</script>



<style lang="scss">

#headers {
    border: 1px solid black;
    width: 100%;
}

</style>
