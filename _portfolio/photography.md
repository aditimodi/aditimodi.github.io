---
title: "PHOTOGRAPHY"
excerpt: "Nature and Birds<br/><img src='../images/photography/tanjuria.jpeg' width='300' height='100'>"
collection: portfolio
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">

<style>
  .designer-grid {
    display: grid;
    grid-template-columns: 1fr 1fr; /* Two equal columns */
    gap: 30px;
    align-items: center;
    margin-bottom: 30px; /* Space between rows */
  }

  .photo-frame {
    position: relative;
    background: white;
    padding: 20px 20px 40px 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    transform: rotate(0deg); /* Straighten the photo frame */
    transition: transform 0.3s ease;
  }

  .photo-frame img {
    width: 100%;
    height: auto;
    object-fit: cover;
  }

  .photo-frame:hover {
    transform: rotate(5deg); /* No rotation on hover */
  }

  .photo-location {
    position: absolute;
    bottom: 0;
    left: 20%;
    transform: translateX(-50%);
    background: #ffffff;
    color: #000000;
    font-size: 0.9em;
    padding: 5px 10px;
    border-radius: 0 0 5px 5px; /* Rounded bottom corners */
    text-align: left;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .photo-location a {
    color: inherit; /* Inherit color from the .photo-location div */
    text-decoration: none; /* Remove underline */
    display: flex;
    align-items: center;
  }

  .photo-location a:hover {
    text-decoration: underline; /* Underline on hover */
  }

  .photo-location i {
    margin-right: 5px; /* Space between icon and text */
  }

  .photo-caption {
    font-size: 1.1em;
    background: #ffffff;
    padding: 20px;
    transform: rotate(0deg); /* No rotation for caption box */
    transition: transform 0.3s ease;
  }
</style>

### Nature and Birds
<!-- First row: photo on the left, description on the right -->
<div class="designer-grid">
  <div class="photo-frame">
    <img src="/images/photography/tanjuria.jpeg" alt="Buddha">
    <div class="photo-location">
      <a href="https://www.google.com/maps/place/Kyoto,+Japan" target="_blank">
        <i class="fas fa-map-marker-alt"></i>Kyoto, Japan
      </a>
    </div> <!-- Location overlay with clickable link -->
  </div>
  <div class="photo-caption">
    <p>Tanjuria: The Blue Butterfly</p>
  </div>
</div>

<!-- Second row: photo on the right, description on the left -->
<div class="designer-grid">
  <div class="photo-caption">
    <p>Tanjuria: The Blue Butterfly</p>
  </div>
  <div class="photo-frame">
    <img src="/images/photography/tanjuria.jpeg" alt="Half-faced">
    <div class="photo-location">
      <a href="https://www.google.com/maps/place/Varanasi,+India" target="_blank">
        <i class="fas fa-map-marker-alt"></i>Varanasi, India
      </a>
    </div> <!-- Location overlay with clickable link -->
  </div>
</div>

<!-- Third row: photo on the left, description on the right -->
<div class="designer-grid">
  <div class="photo-frame">
    <img src="/images/photography/tanjuria.jpeg" alt="Sleeping Beauty">
    <div class="photo-location">
      <a href="https://www.google.com/maps/place/Paris,+France" target="_blank">
        <i class="fas fa-map-marker-alt"></i>Paris, France
      </a>
    </div> <!-- Location overlay with clickable link -->
  </div>
  <div class="photo-caption">
    <p>Tanjuria: The Blue Butterfly</p>
  </div>
</div>
