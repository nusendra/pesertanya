<script>
  let eventName = "";
</script>

<!-- Hero Area Start -->
<div id="hero-area" class="hero-area-bg">
  <div class="container">
    <div class="row">
      <div class="col-md-12 col-sm-12">
        <div class="contents text-center" style="margin-top: 50px;">
          <h2 class="head-title wow fadeInUp" style="margin-bottom: 50px;">
            Mari Berkumpul, Bertanya dan Berdiskusi !
          </h2>
          <div class="row justify-content-md-center">
            <div class="col-md-6">
              <div class="form-group input-group input-group-lg event-name">
                <input
                  :value={eventName}
                  type="text"
                  placeholder="Nama Event"
                  class="form-control text-center border"
                  aria-label="Large"
                  aria-describedby="inputGroup-sizing-sm" />
              </div>
            </div>
          </div>
        </div>
        <div class="img-thumb text-center wow fadeInUp" data-wow-delay="0.6s">
          <img class="img-fluid" src="images/hero-1.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</div>
<!-- Hero Area End -->
