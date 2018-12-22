<template>
  <footer class="footer section">
    <h2 class="section-title">Contact us</h2>
    <div class="container">
      <div class="columns">
        <div class="column">
          <div class="map">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3053.623321393677!2d-111.66989818385068!3d40.061506285089095!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x874da4b37028f61f%3A0x6e66a47d14dd8d37!2sUrban+Retreat+Salon!5e0!3m2!1sen!2sus!4v1545368820423" width="600" height="600" frameborder="0" style="border:0" allowfullscreen></iframe>
          </div>
        </div>
        <div class="column">

          <div class="contact-info" itemscope itemtype="http://schema.org/BeautySalon">
            <div itemprop="name" class="name">Urban Retreat Salon</div>

            <a href="https://www.google.com/maps/place/Urban+Retreat+Salon/@40.0615063,-111.6698982,17z/data=!3m1!4b1!4m5!3m4!1s0x874da4b37028f61f:0x6e66a47d14dd8d37!8m2!3d40.0615022!4d-111.6677095" class="info-item">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48"><path d="M24 4c-7.73 0-14 6.27-14 14 0 10.5 14 26 14 26s14-15.5 14-26c0-7.73-6.27-14-14-14zm0 19c-2.76 0-5-2.24-5-5s2.24-5 5-5 5 2.24 5 5-2.24 5-5 5z"/></svg>
              <div itemprop="address" itemscope itemtype="http://schema.org/PostalAddress">
                <span itemprop="streetAddress">452 North UT-198</span><br>
                <span itemprop="addressLocality">Salem</span>,
                <span itemprop="addressRegion">UT</span> <span itemprop="postalCode">84653</span>
              </div>
            </a>
            
            <a href="tel:385-335-8256" class="info-item">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48"><path d="M13.25 21.59c2.88 5.66 7.51 10.29 13.18 13.17l4.4-4.41c.55-.55 1.34-.71 2.03-.49C35.1 30.6 37.51 31 40 31c1.11 0 2 .89 2 2v7c0 1.11-.89 2-2 2C21.22 42 6 26.78 6 8c0-1.11.9-2 2-2h7c1.11 0 2 .89 2 2 0 2.49.4 4.9 1.14 7.14.22.69.06 1.48-.49 2.03l-4.4 4.42z"/></svg>
              <div itemprop="telephone">(385) 335-8256</div>
            </a>
            
            <a class="info-item" href="mailto:urbanretreatsalem@gmail.com">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48"><path d="M40 8H8c-2.21 0-3.98 1.79-3.98 4L4 36c0 2.21 1.79 4 4 4h32c2.21 0 4-1.79 4-4V12c0-2.21-1.79-4-4-4zm0 8L24 26 8 16v-4l16 10 16-10v4z"/></svg>
              <div itemprop="email">urbanretreatsalem@gmail.com</div>
            </a>
            
            <div itemprop="url" class="is-invisible">urbanretreatsalem.com</div>
          </div>

        </div>
      </div>
    </div>
    <div class="copyright">
      <p>Urban Retreat Salon &copy; 2018 &bullet; Designed &amp; Developed by Jon Garrard</p>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
  .footer {
    background-color: #f8f8f8;
    padding: 3rem 0 0;
  }

  .column {
    padding: 1.25rem;
  }

  .contact-info {
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 100%;
    height: 100%;

    > div,
    > a {
      font-size: 22px;
      font-weight: 300;
      margin: 8px 24px;
      color: #444;
    }

    .name {
      font-weight: 500;
      font-size: 28px;
      position: relative;
      margin-bottom: 20px;
    }
  }

  .info-item {
    display: flex;

    > svg {
      width: 28px;
      height: 28px;
      margin-right: 20px;
      margin-top: 3px;
      fill: #777;
    }
  }

  .map {
    box-shadow: 0 2px 2px 0 rgba(0,0,0,0.14), 0 3px 1px -2px rgba(0,0,0,0.12), 0 1px 5px 0 rgba(0,0,0,0.2);
    border-radius: 3px;
  }

  .copyright {
    text-align: center;
    border-top: solid 3px #fff;
    height: 6rem;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 9rem;
    color: #bbb;
    font-size: 14px;
  }
</style>