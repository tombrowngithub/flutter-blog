<template>
  <div class="home">
    <div class="card-large">
      <img src="../assets/images/large.jpg" alt="">
      <div class="inside-card">
        <div class="frontend">Front-end . 1 Hour ago</div>
        <div class="blog-heading"><h3>Optimizing CSS for faster page loads</h3></div>
        <div class="blog-subheading">
          <p>Not long ago I decided to improve the loading times of my website. It already loads pretty fast, but I knew
            there was still room for improvement and one of them was CSS loading. I will walk you through the process
            and show you how you can improve your load times as well. To see how CSS affects the load time of a webpage
            we first have to know how the browser converts an HTML document into a functional webpage... </p>
          <button class="btn">Read Post</button>
        </div>
      </div>
    </div>
    <div class="post-row">
      <router-link to="/BlogView">
        <div class="card-mini">
          <img src="../assets/images/mini.jpg" alt="">
          <div class="inside-mini">
            <div class="frontend">Front-end . 1 Hour ago</div>
            <div class="blog-heading"><h3>CSS Grid</h3></div>
            <div class="blog-subheading">
              <p>Affects the load time of a webpage we first have to know how the browser converts an HTML document into
                a
                functional webpage... </p>
            </div>
          </div>
        </div>
      </router-link>

      <router-link to="/BlogView">
        <div class="card-mini">
          <img src="../assets/images/mini.jpg" alt="">
          <div class="inside-mini">
            <div class="frontend">Front-end . 1 Hour ago</div>
            <div class="blog-heading"><h3>CSS Grid</h3></div>
            <div class="blog-subheading">
              <p>Affects the load time of a webpage we first have to know how the browser converts an HTML document into
                a
                functional webpage... </p>
            </div>
          </div>
        </div>
      </router-link>

      <router-link to="/BlogView">
        <div class="card-mini">
          <img src="../assets/images/car1.png" alt="">
          <div class="inside-mini">
            <div class="frontend">Front-end . 1 Hour ago</div>
            <div class="blog-heading"><h3>CSS Grid</h3></div>
            <div class="blog-subheading">
              <p>Affects the load time of a webpage we first have to know how the browser converts an HTML document into
                a
                functional webpage... </p>
            </div>
          </div>
        </div>
      </router-link>
    </div>
    <div class="post-row">
      <router-link to="/BlogView">
        <div class="card-mini">
          <img src="../assets/images/mini.jpg" alt="">
          <div class="inside-mini">
            <div class="frontend">Front-end . 1 Hour ago</div>
            <div class="blog-heading"><h3>CSS Grid</h3></div>
            <div class="blog-subheading">
              <p>Affects the load time of a webpage we first have to know how the browser converts an HTML document into
                a
                functional webpage... </p>
            </div>
          </div>
        </div>
      </router-link>

      <router-link to="/BlogView">
        <div class="card-mini">
          <img src="../assets/images/mini.jpg" alt="">
          <div class="inside-mini">
            <div class="frontend">Front-end . 1 Hour ago</div>
            <div class="blog-heading"><h3>CSS Grid</h3></div>
            <div class="blog-subheading">
              <p>Affects the load time of a webpage we first have to know how the browser converts an HTML document into
                a
                functional webpage... </p>
            </div>
          </div>
        </div>
      </router-link>

      <router-link to="/BlogView">
        <div class="card-mini">
          <img src="../assets/images/car1.png" alt="">
          <div class="inside-mini">
            <div class="frontend">Front-end . 1 Hour ago</div>
            <div class="blog-heading"><h3>CSS Grid</h3></div>
            <div class="blog-subheading">
              <p>Affects the load time of a webpage we first have to know how the browser converts an HTML document into
                a
                functional webpage... </p>
            </div>
          </div>
        </div>
      </router-link>
    </div>
    <div class="join-our-team">
      <h2>Join our Team of Writers</h2>
      <p>On dasdas, writers earn a living doing what they love. Getting started is easy. Just pay a one time $25 fee and
        everything is ready to go</p>
      <router-link to="/join">
        <button>Join Us</button>
      </router-link>
    </div>
  </div>
  <router-view/>
</template>
