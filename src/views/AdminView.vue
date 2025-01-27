<template>
    <div class="d-flex vh-100">
      <!-- Sidebar -->
      <nav class="bg-dark text-white p-3" style="width: 250px;">
        <h2 class="text-center text-primary mb-4">Admin Panel</h2>
        <ul class="nav flex-column">
          <li class="nav-item mb-2">
            <a href="#" class="nav-link text-white active">
              <i class="bi bi-house-door-fill me-2"></i> Dashboard
            </a>
          </li>
          <li class="nav-item mb-2">
            <a href="#" class="nav-link text-white">
              <i class="bi bi-people-fill me-2"></i> Manage Users
            </a>
          </li>
          <li class="nav-item mb-2">
            <a href="#" class="nav-link text-white">
              <i class="bi bi-briefcase-fill me-2"></i> Manage Jobs
            </a>
          </li>
          <li class="nav-item mb-2">
            <a href="#" class="nav-link text-white">
              <i class="bi bi-bar-chart-fill me-2"></i> Analytics
            </a>
          </li>
          <li class="nav-item mb-2">
            <a href="#" class="nav-link text-white">
              <i class="bi bi-gear-fill me-2"></i> Settings
            </a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link text-white">
              <i class="bi bi-box-arrow-right me-2"></i> Logout
            </a>
          </li>
        </ul>
      </nav>
  
      <!-- Main Content -->
      <div class="flex-fill p-4 bg-light overflow-auto">
        <!-- Header -->
        <header class="mb-4">
          <h1 class="mb-1">Welcome to the Admin Panel</h1>
          <p class="text-secondary">
            Manage your application efficiently with the tools below.
          </p>
        </header>
  
        <!-- Dashboard Overview -->
        <div class="row g-3 mb-4">
          <div class="col-md-4">
            <div class="card text-center shadow-sm">
              <div class="card-body">
                <h5 class="card-title">Total Users</h5>
                <p class="card-text fs-4">120</p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card text-center shadow-sm">
              <div class="card-body">
                <h5 class="card-title">Total Jobs</h5>
                <p class="card-text fs-4">45</p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card text-center shadow-sm">
              <div class="card-body">
                <h5 class="card-title">Active Sessions</h5>
                <p class="card-text fs-4">10</p>
              </div>
            </div>
          </div>
        </div>
  
        <!-- Manage Content Section -->
        <section>
          <h2>Manage Content</h2>
          <p>This section can include forms, tables, or other tools for managing your app's data.</p>
        </section>
      </div>
    </div>
  </template>
  <style scoped>
  /* Optional customizations can be added here */
  </style>
  