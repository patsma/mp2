<template>
  <div class="loader-wrapper --hidden">
    <div class="loader relative grid h-screen w-full grid-cols-12">
      <div
        class="text-container pointer-events-none z-50 col-span-12 grid h-full w-screen place-content-center text-center mix-blend-overlay"
      >
        <div
          class="title grid w-full content-center text-4xl font-light leading-[110%] text-black md:text-8xl"
        >
          <div class="--text-split">Morten Christensen</div>
        </div>
        <div class="subtitles relative grid">
          <div
            class="subtitle grid content-center font-secondary text-2xl font-normal italic leading-[140%] text-black"
          >
            Digital designer
          </div>
          <div
            class="subtitle absolute top-0 left-1/2 grid w-full -translate-x-1/2 content-center font-secondary text-2xl font-normal italic leading-[140%] text-black"
          >
            UI designer
          </div>
          <div
            class="subtitle absolute top-0 left-1/2 grid w-full -translate-x-1/2 content-center font-secondary text-2xl font-normal italic leading-[140%] text-black"
          >
            Visual designer
          </div>
          <div
            class="subtitle absolute top-0 left-1/2 grid w-full -translate-x-1/2 content-center font-secondary text-2xl font-normal italic leading-[140%] text-black"
          >
            Portfolio
          </div>
        </div>
      </div>
      <div class="loading-text absolute left-1/2 bottom-16 -translate-x-1/2">
        <div class="loading-text__text text-sm leading-[110%]">19%</div>
      </div>
      <div class="loader-images absolute h-full w-full">
        <div
          class="image image-01 center-center absolute h-[20.25rem] w-[36rem]"
        >
          <img
            alt=""
            class="object-cover"
            src="@/assets/img/Image-component.jpg"
          />
        </div>
        <div
          class="image image-02 center-center absolute h-[30.25rem] w-[17rem]"
        >
          <img
            alt=""
            class="object-cover"
            src="@/assets/img/Image-component-v.jpg"
          />
        </div>
        <div
          class="image image-03 center-center absolute h-[20.25rem] w-[36rem]"
        >
          <img
            alt=""
            class="object-cover"
            src="@/assets/img/Image-component.jpg"
          />
        </div>
        <div
          class="image image-04 center-center absolute h-[30.25rem] w-[17rem]"
        >
          <img
            alt=""
            class="object-cover"
            src="@/assets/img/Image-component-v.jpg"
          />
        </div>
        <div
          class="image image-05 center-center absolute h-[20.25rem] w-[36rem]"
        >
          <img
            alt=""
            class="object-cover"
            src="@/assets/img/Image-component.jpg"
          />
        </div>
      </div>
    </div>
    <div
      class="blob-background pointer-events-none fixed top-0 h-screen w-screen"
    >
      <svg
        class="blob1"
        viewBox="0 0 743 607"
        xmlns="http://www.w3.org/2000/svg"
      >
        <g id="Layer_2" data-name="Layer 2">
          <g id="Layer_1-2" data-name="Layer 1">
            <path
              d="M728.77,371.78c4.47-46.67,27.14-96,4-138.25-6.09-11-14.81-20.47-24.57-29.25-12.9-11.59-27.59-22.05-40.43-33.72C645,149.89,632,125.17,614.5,102.49a168.78,168.78,0,0,0-24.61-26.15q-5.43-4.59-11-9c-30.43-24.15-64.69-44.88-103.64-56.91C420-6.62,354.33-3.9,307.68,27.18c-16.79,11.19-30.39,25.35-43.51,40.12-10.58,11.87-20.81,24.06-32.12,35.19-10.11,10-21.07,19.18-33.87,26.53C180,139.5,159,145.67,139.65,154.47a200.79,200.79,0,0,0-35.21,20.58,197.23,197.23,0,0,0-39.27,37.89c-24.45,31.21-38.28,68.85-37.35,106.74.14,5.93.63,11.9.82,17.85a87.19,87.19,0,0,1-1.13,19.56c-2,10.58-7.07,20.52-12.27,30.37C8.17,400.88.76,414.15.06,428.73c-1.23,25.06,17.3,46.53,37.85,64.88,3.43,3.07,6.93,6.05,10.39,8.95,5.5,4.63,11.17,9.26,16.88,13.83l1.1.89c3.06,2.43,6.13,4.86,9.24,7.26,7.82,6,15.82,11.9,24,17.5q5.5,3.74,11,7.26A300,300,0,0,0,137,564.45c22.35,11.37,46.21,19.68,71.9,23,70.34,8.82,140.32-22.52,211.27-18.37,46.56,2.71,90,20.5,135.09,30.86s97.51,12,133.89-13.59c33.53-23.56,44.52-64.25,44.61-101.88S725.16,409.29,728.77,371.78Z"
              fill="#ff19b1"
              opacity="0.5"
              style="isolation: isolate"
            />
          </g>
        </g>
      </svg>
      <svg
        class="blob2"
        viewBox="0 0 809.22 715.21"
        xmlns="http://www.w3.org/2000/svg"
      >
        <g id="Layer_2" data-name="Layer 2">
          <g id="Layer_1-2" data-name="Layer 1">
            <path
              d="M746.85,518.55c24-44,67.06-83.07,61.95-134.33-1.36-13.39-6-26.35-11.91-39.1C789.05,328.31,779,311.84,771.24,295c-13.69-29.89-16.11-59.67-23.83-89.33a180.47,180.47,0,0,0-13.25-36.08c-2.28-4.53-4.63-9.05-7-13.52C707.29,119.49,682.26,84.7,649,56.49c-47.25-39.94-113.06-64.86-172-53.9-21.23,4-40.57,12.16-59.69,21.18-15.4,7.22-30.59,14.92-46.4,21.11-14.16,5.59-28.8,10-44.49,11.86-22.35,2.65-45.58-.11-68.32.43a215.7,215.7,0,0,0-43.31,5.44,211.4,211.4,0,0,0-54.58,20.76C123,103.8,93.52,135,78.53,172.67c-2.35,5.9-4.37,12-6.69,17.9a92.77,92.77,0,0,1-9.32,18.77c-6.46,9.55-15.58,17.21-24.83,24.72-12.6,10.22-25.47,20.16-32.28,34.21-11.74,24.13-2.51,53,10,79.73,2.1,4.46,4.29,8.87,6.47,13.17C25.38,368,29,375,32.72,381.87l.71,1.33c2,3.68,4,7.36,6,11,5.16,9.22,10.57,18.36,16.3,27.31q3.84,6,7.78,11.77a319.75,319.75,0,0,0,19.65,26c17.23,20.58,37.24,38.78,61.14,52.83C209.92,550.38,292,549,360.1,582.88c44.7,22.23,80,58,120.06,87.14s91,52.8,137.54,42.9c42.9-9.07,70.81-44.48,86.7-81.45S727.55,553.93,746.85,518.55Z"
              fill="#ff5019"
              opacity="0.5"
              style="isolation: isolate"
            />
          </g>
        </g>
      </svg>
    </div>
  </div>
</template>
<style lang="scss">
body {
  overflow-x: hidden;
  //min-height: 300vh;
}

.--hidden {
  opacity: 0;
  visibility: hidden;
}

.--text-split {
  overflow: hidden;
}

.subtitle {
  opacity: 0;
  visibility: hidden;
}

.blob-background {
  filter: blur(100px);
  z-index: -1;
  opacity: 0;
  visibility: hidden;

  svg {
    position: absolute;
    width: 100%;
    height: 100%;
    left: 0;
    top: 0;
  }
}

.loading-text {
  opacity: 0;
  visibility: hidden;
}

//.loader-images {
//  opacity: 0;
//  visibility: hidden;
//}
img {
  width: 100%;
  height: 100%;
}

.gs-dev-tools {
  z-index: 999999;
}
</style>
<script>
import gsap from "gsap";
import GSDevtools from "gsap/GSDevTools";
import SplitText from "gsap/SplitText";
import { loading } from "@nuxt/ui-templates";

export default {
  mounted() {
    gsap.registerPlugin(SplitText, GSDevtools);

    const blobsTl = gsap.timeline({ paused: true });
    const masterTl = gsap.timeline({ delay: 1 });
    const imagesTL = gsap.timeline({
      paused: true,
      defaults: { duration: 1 },
    });

    const defaultSplitText = new SplitText(".--text-split", { type: "chars" });
    const defaultSplitTextChars = defaultSplitText.chars;
    const subtitles = gsap.utils.toArray(".subtitle");
    const images = gsap.utils.toArray(".image");
    const loaderWrapper = document.querySelector(".loader-wrapper");
    const blobBackground = document.querySelector(".blob-background");
    const image01 = document.querySelector(".image-01");
    const image02 = document.querySelector(".image-02");
    const image03 = document.querySelector(".image-03");
    const image04 = document.querySelector(".image-04");
    const image05 = document.querySelector(".image-05");

    function timeline() {
      masterTl.set(loaderWrapper, { autoAlpha: 1 });

      masterTl.set(image01, {
        scale: 0,
        transformOrigin: "center center",
      });
      masterTl.set(image02, {
        autoAlpha: 0,
        width: image01.clientWidth,
        height: image01.clientHeight,
      });
      masterTl.set(image03, {
        autoAlpha: 0,
        width: image02.clientWidth,
        height: image02.clientHeight,
      });
      masterTl.set(image04, {
        autoAlpha: 0,
        width: image03.clientWidth,
        height: image03.clientHeight,
      });
      masterTl.set(image05, {
        autoAlpha: 0,
        width: image04.clientWidth,
        height: image04.clientHeight,
      });
      masterTl.to(blobBackground, { autoAlpha: 1 });
      masterTl.from(defaultSplitTextChars, {
        duration: 0.8,
        y: 100,
        ease: "back",
        stagger: {
          from: "center",
          amount: -1.5,
        },
      });
      masterTl.add("show-blob");
      subtitles.forEach((item) => {
        masterTl.to(item, {
          autoAlpha: 1,
          duration: 1,
        });
        masterTl.to(item, {
          autoAlpha: 0,
        });
      });
      // masterTl.add(blobsTl.play(), "show-blob");
      masterTl.add(imagesTL.play(), "show-blob");

      imagesTL.to(image01, {
        scale: 1,
      });
      imagesTL.to(image02, {
        autoAlpha: 1,
        width: image02.clientWidth,
        height: image02.clientHeight,
      });
      imagesTL.to(
        image01,
        {
          autoAlpha: 0,
          width: image02.clientWidth,
          height: image02.clientHeight,
        },
        "<"
      );
      imagesTL.to(image02, {
        autoAlpha: 0,
        width: image01.clientWidth,
        height: image01.clientHeight,
      });
      imagesTL.to(
        image03,
        {
          autoAlpha: 1,
          width: image03.clientWidth,
          height: image03.clientHeight,
        },
        "<"
      );

      imagesTL.to(image04, {
        autoAlpha: 1,
        width: image04.clientWidth,
        height: image04.clientHeight,
      });

      imagesTL.to(
        image03,
        {
          autoAlpha: 0,
          width: image04.clientWidth,
          height: image04.clientHeight,
        },
        "<"
      );

      imagesTL.to(image05, {
        autoAlpha: 1,
        width: image05.clientWidth,
        height: image05.clientHeight,
      });

      imagesTL.to(
        image04,
        {
          // autoAlpha: 0,
          width: image05.clientWidth,
          height: image05.clientHeight,
        },
        "<"
      );

      blobsTl.to(
        ".blob2",
        {
          x: "-=400",
          scale: 2.25,
          rotate: "+=180",
          transformOrigin: "center center",
          duration: 10,
          repeat: -1,
          yoyo: true,
        },
        "show-blob"
      );
      blobsTl.to(
        ".blob1",
        {
          x: "+=300",
          scale: 1.5,
          rotate: "+=140",
          transformOrigin: "center center",
          duration: 10,
          repeat: -1,
          yoyo: true,
        },
        "<"
      );
    }

    timeline();

    // GSDevtools.create();
  },
};
</script>
