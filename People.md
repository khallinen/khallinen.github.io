---
layout: default
title: People
description: Who are we?
---

<style>
  .person-card {
    display: flex; /* Puts image and text side-by-side */
    align-items: center; /* Vertically centers the text */
    gap: 20px; /* Space between image and text */
    margin-bottom: 30px; /* Space between people */
    background: #f9f9f9; /* Optional: light background card */
    padding: 15px; /* Optional: padding inside card */
    border-radius: 8px; /* Optional: rounded corners */
  }

  .person-img {
    width: 200px; /* Force consistent image size */
    height: 200px;
    object-fit: cover; /* Ensures faces aren't squashed */
    border-radius: 50%; /* Optional: Makes images circular */
    flex-shrink: 0; /* Prevents image from shrinking */
  }

  .person-info h3 {
    margin-top: 0;
    margin-bottom: 5px;
  }

  /* Mobile: Stack them vertically on phones */
  @media (max-width: 600px) {
    .person-card { flex-direction: column; text-align: center; }
  }
</style>

<h3>Faculty</h3>

<div class="person-card">
  <img class="person-img" src="{{ '/assets/Images/UOFacultyStaffHeadshots-DSCF2838.jpg' | relative_url }}" alt="Dr. Hallinen">
  <div class="person-info">
    <h3>Dr. Kelsey Hallinen</h3>
    <p>
      Office: Willamette Hall 377<br>
      Email: <a href="mailto:hallinen@uoregon.edu">hallinen@uoregon.edu</a>
    </p>
  </div>
</div>

<h3>Grad Students</h3>

<div class="person-card">
  <img class="person-img" src="{{ '/assets/Images/Hudson_LabWebsite.jpg' | relative_url }}" alt="Hudson">
  <div class="person-info">
    <h3>Hudson Lazzara</h3>
    <p>
      PhD Student, Physics<br>
      Email: <a href="mailto:hlazzara@uoregon.edu">hlazzara@uoregon.edu</a>
    </p>
  </div>
</div>

<div class="person-card">
  <img class="person-img" src="{{ '/assets/Images/Meg_LabWebsite.jpg' | relative_url }}" alt="Meg">
  <div class="person-info">
    <h3>Meg Alberding</h3>
    <p>
      PhD Student, OIMB<br>
      Rotation Student<br>
      Email: <a href="mailto:malb@uoregon.edu">malb@uoregon.edu</a>
    </p>
  </div>
</div>

<h3>Undergraduate Students</h3>

<div class="person-card">
  <img class="person-img" src="{{ '/assets/Images/Anna_LabWebsite.jpg' | relative_url }}" alt="Anna">
  <div class="person-info">
    <h3>Anna McFarlane</h3>
    <p>
      3rd year student, Human Physiology<br>
      Joint with the Parthasarathy Lab
    </p>
  </div>
</div>
