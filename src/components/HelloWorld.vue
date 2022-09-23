<template>
  <section>
    <div>
      <b-button v-b-modal.modal-xl variant="primary">Open Page</b-button>
      <b-modal id="modal-xl" size="xl">
        <div class="container">
          <div class="row">
            <div class="col-md-6">
              <div>
                <VueSlickCarousel :arrows="true" :dots="true">
                  <div><img src="../../images/img-1.jpg" alt="" /></div>
                  <div><img src="../../images/img-2.jpg" alt="" /></div>
                  <div><img src="../../images/img-3.jpg" alt="" /></div>
                </VueSlickCarousel>
              </div>
            </div>
            <div class="col-md-6">
              <p class="color-light">10 DAYS ONLY</p>
              <h3>Special Offer</h3>
              <p>
                Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nemo
                quaerat, distinctio quidem eos sapiente aperiam odit. Maiores
                quia dolorum, laboriosam ea pariatur omnis illum iure!
                Perferendis ad in sapiente ex?
              </p>
              <div class="color-light mt-3">
                <div class="d-flex">
                  <div>
                    <i class="ri-user-3-line"></i>
                  </div>
                  <div>
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                    Nemo quaerat, distinctio quidem eos sapiente aperiam odit.
                  </div>
                </div>
                <div class="d-flex mt-2">
                  <div>
                    <i class="ri-user-3-line"></i>
                  </div>
                  <div>
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                    Nemo quaerat, distinctio quidem eos sapiente aperiam odit.
                  </div>
                </div>
              </div>

              <hr />
              <form>
                <div class="form-group form-group-input">
                  <input
                    type="text"
                    class="form-control"
                    id="formGroupExampleInput2"
                    placeholder="Enter text here"
                  />
                </div>
              </form>

              <form>
                <select
                  class="form-select form-group-input"
                  aria-label="Default select example"
                >
                  <option selected>Enter text here</option>
                  <option value="1">One</option>
                  <option value="2">Two</option>
                  <option value="3">Three</option>
                </select>
              </form>
              <div class="form-check mt-2">
                <input
                  class="form-check-input position-static"
                  type="checkbox"
                  id="blankCheckbox"
                  value="option1"
                />
                <p class="color-blue">Other Hot Deals</p>
              </div>
              <div class="form-check mt-2">
                <input
                  class="form-check-input position-static"
                  type="radio"
                  name="blankRadio"
                  id="blankRadio1"
                  value="option1"
                />
                <p class="color-blue">Other Hot Deals</p> 
              </div>
              <div class="buttons" >
                <button type="button" class="btn btn-danger">SUBMIT</button>
                <button type="button" class="btn btn-outline-danger">KNOW MORE</button>
              </div>
            </div>
          </div>
        </div>
      </b-modal>
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
.color-light {
  color: #c7c7c7;
}
.color-red {
  color: rgb(212, 47, 47);
}
.color-blue{
  color:rgba(49, 72, 245, 1);
}
i {
  background-color: white;
  border-radius: 50%;
  border: 3px solid #c7c7c7;
  padding: 10px;
}
.buttons{
  gap: 1rem !important;
  display: flex;
  margin-top: 1rem;
}
.btn{
  width: 25rem;
}
.form-group-input {
  width: 20rem;
  margin-top: 15px;
}
.slick-dots {
  bottom: 25px !important;
}
</style>