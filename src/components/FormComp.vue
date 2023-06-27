<template>
    <form action="">
        <h2>Name</h2>
        <input type="text">
        <h2>Surname</h2>
        <input type="text">
        <h2>Number</h2>
        <select name="" id="">
            <option value="">+27</option>
            <option value="">+25</option>
            <option value="">+45</option>
            <option value="">+1</option>
        </select>
        <input type="text">
        <h2>Terms and Conditions</h2>
  <input type="checkbox" id="checkbox" v-model="checked" />
  <label for="checkbox">Accepted: {{ checked }}</label>
        <h2>Gender</h2>
  <input type="radio" id="male" value="male" v-model="picked">
  <label for="male">male</label>
  <input type="radio" id="female" value="female" v-model="picked">
  <label for="female">Female</label>
  <br>
  <span>Gender: {{picked}}</span>

    </form>
</template>

<script>
export default {
  data() {
    return { 
        checked: true,
   picked: 'male', multiSelect: ['A']
}

  },
};
</script>