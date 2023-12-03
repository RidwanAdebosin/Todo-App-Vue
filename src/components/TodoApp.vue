<template>
  <div class="container">
    <!-- Heading -->
    <h2 class="heading">My vue to do app</h2>
    <!-- Input -->
    <div class="input">
      <input
        type="text"
        v-model="task"
        placeholder="Enter task"
        class="form-control"
      />
    </div>
  </div>

  <!-- Table -->
  <table>
    <tbody>
      <tr>
        <th scope="row">1</th>
        <td></td>
        <td></td>
        <td></td>
      </tr>

      <tr>
        <th scope="row">2</th>
        <td></td>
        <td></td>
        <td></td>
      </tr>

      <tr>
        <th scope="row">3</th>
        <td></td>
        <td></td>
        <td></td>
      </tr>
    </tbody>
  </table>
</template>

<script>
export default {
  name: "TodoApp",
};
</script>

<style></style>
