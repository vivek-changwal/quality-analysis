<template>
  <div class="dizme_tm_section" id="process">
    <div class="dizme_tm_process">
      <div class="container">
        <div class="list">
          <ul>
            <li class="wow fadeInUp" data-wow-duration="1s">
              <div class="list_inner">
                <div class="icon">
                  <span v-html="dark ? pixelPerfectDark : pixelPerfectLight">
                  </span>
                </div>
                <div class="title">
                  <h3>Expertise</h3>
                </div>
                <div class="text">
                  <p>
                    Our team comprises seasoned professionals with diverse skills and deep 
                    industry knowledge.
                  </p>
                </div>
              </div>
            </li>
            <li
              class="wow fadeInUp"
              data-wow-duration="1s"
              data-wow-delay="0.2s"
            >
              <div class="list_inner">
                <div class="icon">
                  <span v-html="dark ? highQualityDark : highQualityLight">
                  </span>
                </div>
                <div class="title">
                  <h3>Innovation</h3>
                </div>
                <div class="text">
                  <p>
                    Embracing the latest technologies and trends, we strive for innovation in
                    every aspect of our work.
                  </p>
                </div>
              </div>
            </li>
            <li
              class="wow fadeInUp"
              data-wow-duration="1s"
              data-wow-delay="0.4s"
            >
              <div class="list_inner">
                <div class="icon">
                  <span v-html="dark ? awesomeIdeaDark : awesomeIdeaLight">
                  </span>
                </div>
                <div class="title">
                  <h3>Quality Assurance</h3>
                </div>
                <div class="text">
                  <p>
                    Rigorous testing protocols, attention to detail,
                    and a focus on excellence are at the core of everything we do.
                  </p>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import {
  awesomeIdeaDark,
  awesomeIdeaLight,
  highQualityDark,
  highQualityLight,
  pixelPerfectDark,
  pixelPerfectLight,
} from "@/svg";
export default {
  name: "ProcessComponent",
  data() {
    return {
      pixelPerfectLight,
      highQualityDark,
      awesomeIdeaDark,
      pixelPerfectDark,
      awesomeIdeaLight,
      highQualityLight,
    };
  },
  components: {},
  props: {
    dark: { type: Boolean },
  },
};
</script>
