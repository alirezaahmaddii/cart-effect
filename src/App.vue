<template>
  <div class="container">
  <div class="row row-cols-1 row-cols-md-4 ">
    <div class="col" v-for="items in list">
      <div class="scrollShow  mycart ">
        <figure>
        <img :src="items.img" class="card-img-top" :alt="items.alt">
        </figure>
<!--        <div class="card-body">-->
<!--          <h5 class="card-title">Card title</h5>-->
<!--          <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>-->
<!--        </div>-->
      </div>
    </div>

  </div>
  </div>
</template>
<script>
export default {
  data:() =>({
    list:[
      {
        img:'/media/image/logo-1.png',
        alt:'lg1',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg2',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg3',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg4',
      },
      {
        img:'/media/image/logo-5.png',
        alt:'lg5',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg6',
      },
      {
        img:'/media/image/logo-5.png',
        alt:'lg7',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg8',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg9',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg11',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg12',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg12',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg11',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-5.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-5.png',
        alt:'lg7',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg8',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg9',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg11',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg12',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg12',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg11',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-5.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg9',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg11',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg12',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg12',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg11',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-5.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-5.png',
        alt:'lg7',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg8',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg9',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg11',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg12',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg12',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg11',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-5.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg1',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg2',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg3',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg4',
      },
      {
        img:'/media/image/logo-5.png',
        alt:'lg5',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg6',
      },
      {
        img:'/media/image/logo-5.png',
        alt:'lg7',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg8',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg9',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg11',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg12',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg12',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg11',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-5.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-5.png',
        alt:'lg7',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg8',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg9',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg11',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg12',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg12',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg11',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-5.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg9',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg11',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg12',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg12',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg11',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-5.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-5.png',
        alt:'lg7',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg8',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg9',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg11',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg12',
      },
      {
        img:'/media/image/logo-3.png',
        alt:'lg12',
      },
      {
        img:'/media/image/logo-4.png',
        alt:'lg11',
      },
      {
        img:'/media/image/logo-1.png',
        alt:'lg-10',
      },
      {
        img:'/media/image/logo-5.png',
        alt:'lg-10',
      },
    ]
  }),
  methods:{
    companyScroll() {
      let scrollShow = {
        items: [], // arary of objects containing DOM element and parameters for scrollShow
        delay: 0.01, // time delay (seconds) on simutaneously showing elements
        default_element_percent: 5, // default percentage of element in viewport to be "in view"
        default_viewport_percent: 10, // default percentage of viewport to be used for "in view checking"
        hide_on_scroll_back: false, // hide if scrolling back up

        // populate this.items to keep track of scrollShow elements
        addItems: function (classname = "scrollShow") {
          let elements = document.getElementsByClassName(classname)
          for (let i = 0; i < elements.length; i++) {
            const el = elements[i]
            const showClass = el.getAttribute('scroll-show') || 'show'
            let elPercent = parseInt(el.getAttribute('scroll-show') || this.default_element_percent)
            let vpPercent = parseInt(el.getAttribute('scroll-show') || this.default_viewport_percent)
            let item = {
              element: el,
              showClass: showClass,
              elPercent: elPercent,
              vpPercent: vpPercent,
              top: null,
              height: null,
              keyY: null
            }
            item = this.updateRect(item)
            this.items.push(item)
          }
          this.onScroll()
        },

        // update scrollShow elements rectangular position
        updateRect: function (item) {
          const rect = item.element.getBoundingClientRect()
          item.top = rect.top + scrollY
          item.height = rect.height
          item.keyY = item.top + item.height * item.elPercent / 100 - innerHeight * (1 - item.vpPercent / 100)
          return item
        },

        onResize: function () {
          for (let i = 0; i < this.items.length; i++) {
            this.items[i] = this.updateRect(this.items[i])
          }
          this.onScroll()
        },

        onScroll: function () {
          const isAfterY = this.items.map(function (item) {
            return item.keyY <= scrollY
          })
          const alreadyShown = this.items.map(function (item) {
            return item.element.classList.contains(item.showClass)
          })

          let count = 0
          for (let i = 0; i < isAfterY.length; i++) {
            const showClass = this.items[i].showClass
            let el = this.items[i].element
            el.style.transitionDelay = null
            if (isAfterY[i] && !alreadyShown[i]) {
              el.style.transitionDelay = `${this.delay * count}s`
              count++
              el.classList.add(showClass)
            } else if (this.hide_on_scroll_back && !isAfterY[i] && alreadyShown[i]) {
              el.classList.remove(showClass)
            }
          }
        },
      };

// listens to window resize and scroll events
      window.addEventListener('resize', () => scrollShow.onResize());
      window.addEventListener('scroll', () => scrollShow.onScroll());
      scrollShow.addItems();
      scrollShow.hide_on_scroll_back = true
    },


  },
  mounted() {
    this.companyScroll();

  }
}
</script>

<style lang="scss">
body *{
  background: black;
}
.mycart{
  border: none;
}
img{
  width: 77% !important;
}
.scrollShow {
  opacity: 0;
  transition: 2s all ease-in-out;
  //transform:rotateY(90deg);
  overflow: hidden;
  transform: translate(40px,-40px) rotate3d(1,1,0,50deg);

}
.show {
  opacity: 1;
  overflow: hidden;
  transition: 2s all ease-in-out;
  //transform: rotateY(0deg);
  //transform-origin: bottom left;
transform: translate(0,0) rotate3d(0,0,0,50deg);
}


.scrollShow .show {
  opacity: 1;
  //transform:rotateY(-90deg);
  overflow: hidden;
  transition: 2s all ease-in-out;
  //transform-origin: bottom left;
}

</style>