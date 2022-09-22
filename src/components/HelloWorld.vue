<template>
  <section>
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <div>
            <VueSlickCarousel :arrows="true" :dots="true">
              <div><img src="../../images/category-1.jpg" alt="" /></div>
              <div><img src="../../images/category-2.jpg" alt="" /></div>
              <div><img src="../../images/category-3.jpg" alt="" /></div>
            </VueSlickCarousel>
          </div>
        </div>
        <div class="col-md-6">
          <p>10 DAYS ONLY</p>
          <h3>Special Offer</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nemo
            quaerat, distinctio quidem eos sapiente aperiam odit. Maiores quia
            dolorum, laboriosam ea pariatur omnis illum iure! Perferendis ad in
            sapiente ex?
          </p>
          <hr />
          <form>
            <div class="form-group">
              <label for="formGroupExampleInput">Example label</label>
              <input
                type="text"
                class="form-control"
                id="formGroupExampleInput"
                placeholder="Example input"
              />
            </div>
            <div class="form-group">
              <label for="formGroupExampleInput2">Another label</label>
              <input
                type="text"
                class="form-control"
                id="formGroupExampleInput2"
                placeholder="Another input"
              />
            </div>
          </form>
          
          <form>
            <div class="form-group"></div>
            <div class="form-group">
              <label for="exampleFormControlSelect1">Example select</label>
              <select class="form-control" id="exampleFormControlSelect1">
                <option>1</option>
                <option>2</option>
                <option>3</option>
                <option>4</option>
                <option>5</option>
              </select>
            </div>
            <div class="form-check">
              <input
                class="form-check-input position-static"
                type="checkbox"
                id="blankCheckbox"
                value="option1"
              />
              Other Hot Deals
            </div>
            <div class="form-check">
              <input
                class="form-check-input position-static"
                type="radio"
                name="blankRadio"
                id="blankRadio1"
                value="option1"
              />
              Other Hot Deals
            </div>
          </form>
          <div>
            
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel.css";
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";

export default {
  name: "MyComponent",
  components: { VueSlickCarousel },
};
</script>


<style scoped>
:root {
  --light: #c7c7c7;
  --primary: rgba(49, 72, 245, 1);
}
body {
  background: #f5f5f8 !important;
  font-family: "Inter-Medium" !important;
}
h1,
h2,
h3,
h4,
h5,
h6,
p,
figure {
  margin: 0 !important;
}
</style>