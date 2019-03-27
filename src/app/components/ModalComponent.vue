<template>

      <div>
      <form id="new-entry">
        <ul>
          <li>
            <label>Last Name </label>
            <input type="text" placeholder="Last Name..." />
          </li>
          <li>
            <label>First Name</label>
            <input type="text" placeholder="First Name" />
          </li>
          <br />
          <li>
            <label>Case File # </label>
            <input type="text" placeholder="Case File # " />
          </li>
          <li>
            <label>DA Supervisor </label><input type="text" placeholder="DA Supervisor" />
          </li>
          <br />
          <li>
            <label>Date Filed </label>
            <input type="text" placeholder="Date Filed" />
          </li>
          <li>
            <label>Probation Ends </label>
            <input type="text" placeholder="Probation Ends" />
          </li>
          <br />
          <li>
            <label>Reference Result </label>
            <input type="text" placeholder="Reference Result" />
          </li>
          <li>
            <label>Successful Contact? </label>
            <input type="text" placeholder="Successful Contact?" />
          </li>
          <br />
          <li>
            <label>Restitution/Fees/Fines</label> 
            <input type="text" placeholder="Restitution/Fees/Fines" />
          </li>
          <li>
            <label>Failure too... </label>
            <input type="text" placeholder="Failure too... " />
          </li>
          <br />
          <li>
            <label>Notes: </label>
            <input type="text" placeholder="Notes" />
          </li>  
        </ul>
      </form>
      <div class="buttons">  
        <button>Cancel</button> 
        <button>Submit</button>    
      </div>
      </div>

</template>



<script>
export default {
  name: 'ModalComponent'
}
</script>



<style lang="scss" scoped>

  #new-entry {
    border: 2px solid black;
  }
 
  .buttons {
    display: flex;
    justify-content: flex-end;
    border: 2px solid black;
  }

</style>
