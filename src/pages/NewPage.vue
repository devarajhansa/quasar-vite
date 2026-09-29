<script setup>


const employee = {
  name: 'Gary',
  age: 28,
  address: {
    city: 'xyz city',
  }
};

const { name, age, address: { city } } = employee;
console.log(name, age, city); // Output: Gary

const add = (...numbers) => {
  return numbers.reduce((acc, n) => acc + n, 0);
};

console.log('add', add(1, 2, 3, 4, 5));

const nums = [1, 2, 3, 4, 5];
const [ first, ...rest ] = nums;
console.log('first', first);
console.log('rest', rest);


</script>

<template>
  <div>A New Page Js</div>
</template>