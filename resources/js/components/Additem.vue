<template>
  <!-- Add Form -->
  <div class="py-8 px-2 lg:px-6">
  <h1 class="text-center p-2 text-xl uppercase font-semibold">Add Item</h1>
    <form class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-2">
      <input
        type="text"
        name="phone"
        placeholder="Phone number"
        class="p-2 outline-0 border border-gray-300"
      />
      <input
        type="number"
        name="duration"
        placeholder="Duration"
        class="p-2 outline-0 border border-gray-300 rounded-md"
      />

      <select type="status" name="status" class="select outline-0 border border-gray-300">
        <option disabled selected>Add Status</option>
        <option>In-call,</option>
        <option>hold</option>
        <option>call back</option>
        <option>Lisa</option>
        <option>do not call</option>
      </select>
      <button type="submit" class="p-2 bg-green-700 uppercase font-semibold text-white border border-gray-300 rounded-md">
        Add Item
      </button>
    </form>
  </div>
</template>
<script>
export default {};
</script>
