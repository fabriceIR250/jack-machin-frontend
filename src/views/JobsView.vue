<template>
    <div class="container my-5">
      <h1 class="text-center mb-4">Available Jobs</h1>
  
      <!-- Search Bar -->
      <div class="mb-4">
        <input
          class="form-control"
          type="text"
          placeholder="Search for jobs..."
        />
      </div>
  
      <!-- Job Listings -->
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="card h-100 shadow-sm">
            <div class="card-body">
              <h5 class="card-title">Frontend Developer</h5>
              <p class="card-text">
                <strong>Company:</strong> Tech Corp <br />
                <strong>Location:</strong> New York
              </p>
              <button class="btn btn-primary" disabled>Apply Now</button>
            </div>
          </div>
        </div>
  
        <div class="col-md-4 mb-4">
          <div class="card h-100 shadow-sm">
            <div class="card-body">
              <h5 class="card-title">Backend Engineer</h5>
              <p class="card-text">
                <strong>Company:</strong> Innovate Ltd <br />
                <strong>Location:</strong> San Francisco
              </p>
              <button class="btn btn-primary" disabled>Apply Now</button>
            </div>
          </div>
        </div>
  
        <div class="col-md-4 mb-4">
          <div class="card h-100 shadow-sm">
            <div class="card-body">
              <h5 class="card-title">Full Stack Developer</h5>
              <p class="card-text">
                <strong>Company:</strong> CodeWorks <br />
                <strong>Location:</strong> Remote
              </p>
              <button class="btn btn-primary" disabled>Apply Now</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <style>
  .card {
    border-radius: 10px;
  }
  .card-body {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }

  </style>
  