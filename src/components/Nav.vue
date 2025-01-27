<template>
    <!-- Top Navbar -->
    <nav class="navbar bg-light py-2 border-bottom">
      <div class="container-fluid">
        <span class="navbar-text">
          <i class="bi bi-telephone-fill"></i> +1 (234) 567-890 | 
          <i class="bi bi-envelope-fill"></i> support@jackmachin.com
        </span>
        <div>
          <button class="btn btn-outline-primary me-2">Login</button>
          <button class="btn btn-primary">Sign Up</button>
        </div>
      </div>
    </nav>
  
    <!-- Navbar with Bootstrap classes -->
    <nav class="navbar navbar-expand-lg bg-black">
      <div class="container-fluid">
        <a class="navbar-brand text-white" href="#">Jack Machin</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <router-link class="nav-link text-white" to="/" active-class="active-link">
                <i class="bi bi-house-door-fill"></i> Home
              </router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link text-white" to="/jobs" active-class="active-link">
                <i class="bi bi-briefcase-fill"></i> Jobs & Employers
              </router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link text-white" to="/about" active-class="active-link">
                <i class="bi bi-info-circle-fill"></i> About
              </router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link text-white" to="/contact" active-class="active-link">
                <i class="bi bi-envelope-fill"></i> Contact Us
              </router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </template>
  
  <style>
  /* Custom class for active links */
  .active-link {
    color: white !important;
    background: rgba(7, 85, 230, 0.788) !important;
    font-weight: bold !important;
    border-radius: 5px;
  }
  </style>
  