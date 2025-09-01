<template>
  <div class="content_holder">
    <div class="content_second_background">
      <div class="content_area clearfix">
        <div
          id="row-290604-1"
          class="content_block_background template_builder"
        >
          <section class="content_block clearfix">
            <section id="row-290604-1-content" class="content left">
              <div class="breadcrumb">
                <div itemscope itemtype="http://data-vocabulary.org/Breadcrumb">
                  <a class="icon-home" href="../index.html" itemprop="url"
                    ><span
                      itemprop="title"
                      title="Unique Construction &amp; Contracting LLC"
                      >Home</span
                    ></a
                  >
                  <span class="icon-angle-right"></span>
                  <div
                    itemscope
                    itemprop="child"
                    itemtype="http://data-vocabulary.org/Breadcrumb"
                  >
                    <span itemprop="title" title="News">News</span>
                    <meta itemprop="name" content="News" />
                    <meta itemprop="url" content="https://uniqueom.com/news/" />
                  </div>
                </div>
              </div>
              <div class="row clearfix"></div>
              <div class="row clearfix">
                <div class="row">
                  <div class="box one">
                    <!-- blog box-->
                    <article class="blog_list loop" id="post-3989">
                      <section class="first_section">
                        <div class="date_box">
                          <span class="day">07</span
                          ><span class="year">Mar 2021</span>
                        </div>
                      </section>
                      <section class="article_section">
                        <div class="blog-head-line clearfix">
                          <div class="post-title-holder">
                            <!-- blog headline-->
                            <h2>
                              <a href="../hse-buliton/index.html" rel="bookmark"
                                >HSE Bulletin</a
                              >
                            </h2>
                            <!-- / blog headline-->
                            <!-- meta data -->
                            <div class="post_data">
                              <!-- user -->
                              <span
                                class="icon-user user margin-right20 vcard author"
                                ><span class="fn"
                                  ><a
                                    href="../author/siteadmin/index.html"
                                    title="Posts by Site Admin"
                                    rel="author"
                                    >Site Admin</a
                                  ></span
                                ></span
                              >
                              <!-- categories -->
                              <span class="icon-flow-cascade categories"
                                ><a
                                  href="../category/projects/index.html"
                                  rel="category tag"
                                  >Projects</a
                                ></span
                              >
                            </div>
                            <!-- / end div  .post_data -->
                            <meta itemprop="name" content="HSE Bulletin" />
                            <meta
                              itemprop="datePublished"
                              content="March 7, 2021"
                            />
                            <meta
                              itemprop="url"
                              content="https://uniqueom.com/hse-buliton/"
                            />
                            <meta
                              itemprop="image"
                              content="https://uniqueom.com/wp-content/uploads/2021/03/Unique.jpg"
                            />
                            <meta itemprop="author" content="Site Admin" />
                          </div>
                          <!-- / end div  .post-title-holder -->
                        </div>
                        <!-- / end div  .blog-head-line -->
                        <!-- <div class="imgeffect aligncenter">
                          <a
                            id="lightbox-813474"
                            class="icon-zoom-in lightbox_"
                            data-group="image_3991"
                            title="Enlarge Image"
                            data-title="HSE Bulletin"
                            data-description=""
                            data-thumbnail="https://uniqueom.com/wp-content/uploads/2021/03/Unique-75x50.jpg"
                            data-thumbTooltip=""
                            data-scaleUp=""
                            data-href=""
                            data-width=""
                            data-height=""
                            data-flashHasPriority=""
                            data-poster=""
                            data-autoplay=""
                            data-audiotitle=""
                            href="../wp-content/uploads/2021/03/Unique.jpg"
                          ></a>
                          <a
                            href="../hse-buliton/index.html"
                            class="icon-link"
                            title="HSE Bulletin"
                            rel="bookmark"
                          ></a>
                          <img
                            src="../wp-content/uploads/2021/03/Unique-740x422.jpg"
                            alt=""
                            class=""
                          />
                        </div> -->
                      </section>
                    </article>
                    <!-- / blog box-->
                  </div>
                </div>
              </div>
            </section>
            <section
              id="row-290604-1-sidebar"
              class="sidebar right sticky"
            ></section>
          </section>
        </div>
      </div>
      <!-- / end div .content_area -->
      <div class="content_footer footer_widgets_holder footer-290604">
        <section class="footer_widgets clearfix footer-widgets-290604 clearfix">
          <div class="row clearfix footer_widgets_row">
            <div id="footer-column-1" class="box three"></div>
            <div id="footer-column-2" class="box three">
              <div class="box one footer clearfix widget widget_text">
                <div class="textwidget"></div>
              </div>
            </div>
            <div id="footer-column-3" class="box three"></div>
          </div>
        </section>
      </div>
    </div>
    <!-- / end div .content_second_background -->
  </div>
</template>

<script>
export default {
  mounted() {
    this.$nextTick(() => {
      // Initialize FlexSlider (moved from inline script inside template)
      try {
        jQuery("#slider-562252").flexslider({
          animation: "slide",
          controlsContainer: "#slider-562252 .flex-nav-container",
          slideshow: true,
          slideshowSpeed: 8 * 1000,
          smoothHeight: true,
          directionNav: true,
          controlNav: false,
          prevText: '<span class="icon-left-open"></span>',
          nextText: '<span class="icon-right-open"></span>',
          start: function (slider) {
            slider.parents(".flex-container:eq(0)").removeAttr("style");
            if (typeof jQuery.waypoints === "function")
              jQuery.waypoints("refresh");
          },
          after: function () {
            if (typeof jQuery.waypoints === "function")
              jQuery.waypoints("refresh");
          },
        });
      } catch (e) {
        // ignore if flexslider not available yet
      }

      // Initialize testimonial carousel (moved from inline script inside template)
      try {
        if (jQuery("#testimonial-carousel-166114-155252").length) {
          jQuery("#testimonial-carousel-166114-155252").rt_start_carousels(
            1,
            ""
          );
        }
      } catch (e) {
        // ignore if carousel plugin not available yet
      }
    });
  },
};
</script>

<style></style>
