<template>
  <div class="card">
    <div class="card-image">
      <figure class="image is-square">
        <img src="https://picsum.photos/800/800?image=823" alt="Placeholder image">
        <figcaption class="title is-4">Jewelz</figcaption>
      </figure>
    </div>
    <div class="card-content">
      <div class="content">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque magni id omnis natus! Aliquid!</p>
        <ul>
          <li>
            <a href="instagram.com" target="_blank" class="instagram"><svg viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg"><title>Instagram</title><path d="M1152 896q0-106-75-181t-181-75-181 75-75 181 75 181 181 75 181-75 75-181zm138 0q0 164-115 279t-279 115-279-115-115-279 115-279 279-115 279 115 115 279zm108-410q0 38-27 65t-65 27-65-27-27-65 27-65 65-27 65 27 27 65zM896 266q-7 0-76.5-.5t-105.5 0-96.5 3-103 10T443 297q-50 20-88 58t-58 88q-11 29-18.5 71.5t-10 103-3 96.5 0 105.5.5 76.5-.5 76.5 0 105.5 3 96.5 10 103T297 1349q20 50 58 88t88 58q29 11 71.5 18.5t103 10 96.5 3 105.5 0 76.5-.5 76.5.5 105.5 0 96.5-3 103-10 71.5-18.5q50-20 88-58t58-88q11-29 18.5-71.5t10-103 3-96.5 0-105.5-.5-76.5.5-76.5 0-105.5-3-96.5-10-103T1495 443q-20-50-58-88t-88-58q-29-11-71.5-18.5t-103-10-96.5-3-105.5 0-76.5.5zm768 630q0 229-5 317-10 208-124 322t-322 124q-88 5-317 5t-317-5q-208-10-322-124t-124-322q-5-88-5-317t5-317q10-208 124-322t322-124q88-5 317-5t317 5q208 10 322 124t124 322q5 88 5 317z"/></svg></a>
          </li>
          <li>(555) 555-5555</li>
          <li>
            <a href="" class="button is-outlined">Book now</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .card {
    border-radius: 3px;
    box-shadow: 0 2px 2px 0 rgba(0,0,0,0.14), 0 3px 1px -2px rgba(0,0,0,0.12), 0 1px 5px 0 rgba(0,0,0,0.2);
  }

  .card-image {
    border-radius: 3px;
    overflow: hidden;
    width: 94%;
    margin: 30px auto -30px;
    transform: translateY(-30px);
    box-shadow: 0 4px 5px 0 rgba(0,0,0,0.14), 0 1px 10px 0 rgba(0,0,0,0.12), 0 2px 4px -1px rgba(0,0,0,0.3);
  }

  .image {
    position: relative;
  }

  figcaption {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    padding: 10px 20px;
    color: rgba(255,255,255,0.7);
  }

  .card-content {
    padding: 2.5rem;
  }

  .content {
    ul {
      margin: 0;
      list-style: none;
    }

    li {
      padding: 0;
    }

    .button {
      background-color: white;
      border-color: #333;
      border-width: 2px;
      border-radius: 3px;
      color: #444;
      transition: all .15s ease-out;

      &:hover,
      &:active,
      &:focus {
        background-color: #333;
        color: white;
      }
    }
  }

  .instagram svg{
    width: 32px;
  }
</style>