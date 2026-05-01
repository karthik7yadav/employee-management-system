<template>
  <div class="container mt-4">
    <h2 class="text-center mb-4">Employee Management System</h2>
    <EmployeeManager />
  </div>
</template>

<script>
import EmployeeManager from "./components/EmployeeManager.vue";

export default {
  components: { EmployeeManager }
};
</script>

<style>
body {
  background: linear-gradient(to right, #eef2f3, #dfe9f3);
  font-family: 'Segoe UI', sans-serif;
}

h2 {
  font-weight: 600;
  color: #333;
}

.card {
  border-radius: 15px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.1);
  border: none;
}

input {
  border-radius: 8px !important;
}

.btn {
  border-radius: 8px;
  transition: 0.3s;
}

.btn:hover {
  transform: scale(1.05);
}

.table {
  border-radius: 10px;
  overflow: hidden;
}

.table th {
  background-color: #343a40;
  color: white;
  text-align: center;
}

.table td {
  text-align: center;
  vertical-align: middle;
}

tr:hover {
  background-color: #f1f5f9;
  transition: 0.2s;
}
</style>