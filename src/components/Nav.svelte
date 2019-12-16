<script>
  import Hero from "./Hero.svelte";

  let collapsed = false;

  let navbarToggler = "navbar-toggler collapsed";
  let ariaExpanded = "false";
  let navbarCollapse = "collapse navbar-collapse";

  const toggleNavbar = () => {
    collapsed = !collapsed;

    if (collapsed) {
      navbarToggler = "navbar-toggler";
      ariaExpanded = "true";
      navbarCollapse = "collapse navbar-collapse show";
    } else {
      navbarToggler = "navbar-toggler collapsed";
      ariaExpanded = "false";
      navbarCollapse = "collapse navbar-collapse";
    }
  };
</script>

<header id="header-wrap">
  <!-- Navbar Start -->
  <nav class="navbar navbar-expand-md bg-inverse fixed-top scrolling-navbar">
    <div class="container">
      <!-- Brand and toggle get grouped for better mobile display -->
      <a href="index.html" class="navbar-brand">
        <img src="images/logo.png" alt="" />
      </a>
      <button
        on:click={toggleNavbar}
        class={navbarToggler}
        type="button"
        data-toggle="collapse"
        data-target="#navbarCollapse"
        aria-controls="navbarCollapse"
        aria-expanded={ariaExpanded}
        aria-label="Toggle navigation">
        <i class="lni-menu" />
      </button>
      <div class={navbarCollapse} id="navbarCollapse">
        <ul class="navbar-nav mr-auto w-100 justify-content-end clearfix">
          <li class="nav-item active">
            <a class="nav-link" href="#hero-area">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- Navbar End -->

  <Hero />
</header>
