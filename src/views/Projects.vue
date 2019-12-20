<template>

  <b-container class="bv-example-row">
      <br>
      <br>
      <h4>What kind of projects does Stemformatics offer?</h4>
        <b-container class="bv-example-row">
          <b-row>
              <b-col></b-col>
              <b-col></b-col>
              <b-col></b-col>
          </b-row>
        <br>
        <br>
        </b-container>
      <b-row>
        <b-col>
          <div class="card" >
            <div class="card-body">
              <h5 class="card-title" style="text-align: left;">Interactive graphing</h5>
              <p class="card-text" style="text-align: left;">We need a new way to plot relationships between data points and sample groups. Part of the role will be to introduce modern plotting libraries to allow for faster interactions between user and data. This will add new opportunities to navigate across the collated data series housed by Stemformatics in the ‘atlas’ projects.  Some of the graphing will include implementation of packages to cluster and view data on dendrograms, heat maps, scatter plots etc.</p>
              <div class="embed-responsive embed-responsive-16by9">
                <iframe class="embed-responsive-item" src="https://www.stemformatics.org/atlas" allowfullscreen></iframe>
              </div>
              <a href="https://www.stemformatics.org/atlas" class="card-link"><p style="text-align: left; color:orange;">Stemformatics iMAC Atlas</p></a>
            </div>
          </div>
        </b-col>
      </b-row>

      <br>
      <br>

      <b-row>
        <b-col>
          <div class="card" >
            <div class="card-body">
              <h5 class="card-title" style="text-align: left;">Curation of underlying metadata</h5>
              <!-- <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6> -->
              <p class="card-text" style="text-align: left;">Stemformatics has an extensive and well curated set of data descriptions, however these are poorly harmonised. This project will provide some automated reviewing and updating of metadata fields associated with different sample classes. The platform would benefit from supporting third parties who wish to directly upload data to the platform. Both of these features require validation/checking mechanism in order to ensure reliable and accurate data is ingested into our system.</p>
              <div class="embed-responsive embed-responsive-16by9">
                <iframe class="embed-responsive-item" src="https://www.stemformatics.org/datasets/search" allowfullscreen></iframe>
              </div>
            </div>
          </div>
        </b-col>
      </b-row>

      <br>
      <br>

      <b-row>
        <b-col>
          <div class="card" >
            <div class="card-body">
              <h5 class="card-title" style="text-align: left;">API Authorization</h5>
              <!-- <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6> -->
              <p class="card-text" style="text-align: left;">Future iterations of the data portal will include the ability for different parties to gain access to data outside of the user interface application. In order for this to work, a means of authentication will be required. (Json web tokens etc.)</p>
              <div class="embed-responsive embed-responsive-16by9">
                <iframe class="embed-responsive-item" src="https://api-dp.stemformatics.org/" allowfullscreen></iframe>
              </div>
            </div>
          </div>
        </b-col>
      </b-row>

      <br>
      <br>

  </b-container>
      

</template>

<style scoped>
.card {
  width: 100%;
}
p {
  color: black;
}
</style>
