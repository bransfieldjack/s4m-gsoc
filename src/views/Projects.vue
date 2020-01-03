<template>
  <div>
  <b-container>
    <b-row>

    <b-col sm="3">
      <b-row>
		<ul>
			<br>
			<br>
			<br>
			<hr>
			<li style="text-align: left; font-weight: bold; color: #a64dff; text-decoration: none;"><a href="#interactive_graphing" style="color: #a64dff;">Interactive Graphing</a></li>
			<hr>
			<li style="text-align: left; font-weight: bold; color: #a64dff; text-decoration: none;"><a href="#metadata_curation" style="color: #a64dff;">Metadata Curation</a></li>
			<hr>
			<li style="text-align: left; font-weight: bold; color: #a64dff; text-decoration: none;"><a href="#api_authorization" style="color: #a64dff;">API Authorization</a></li>
			<hr>
		</ul>
      </b-row>
    </b-col>

	<b-col sm="1">
	</b-col>

    <b-col sm="8" class="right">
    
			<br>
			<br>
			<br>
			<br>
			<h4>What kind of projects does Stemformatics offer?</h4>

			<b-row>
			
			<br>
			<br>
			<!-- <b-container class="bv-example-row">
				<b-row>
					<b-col></b-col>
					<b-col></b-col>
					<b-col></b-col>
				</b-row>
			<br>
			<br>
			</b-container> -->
			<b-row>

			<b-col>
				<a id="interactive_graphing">
					<div class="card" >
						<div class="card-body">
							<h5 class="card-title" style="text-align: left;">Interactive graphing</h5>
							<p class="card-text" style="text-align: left;">We need new ways to plot data in Stemformatics, which often represent measurements of gene expression in biological samples. In this project, we aim to introduce modern plotting libraries to allow for faster interactions between user and data. Many of the existing plots on the website were implemented years ago and are now out-dated, and we want to replace them with more modern approaches. An example of a new approach implemented currently on the website can be found in our <a href="https://www.stemformatics.org/atlas" target="_blank">"atlas"</a> page. This page uses <a href="https://vuejs.org/" target="_blank">vuejs</a> to handle user interactions and <a href="https://plot.ly/" target="_blank">plotlyjs</a> to perform the plotting.</p>
							<p class="card-text" style="text-align: left;">In programming terms, this project is primarily a data visualisation problem, which requires some understanding of what information is being conveyed and how to make this most effective. Some of the graphing may require some summarising or clustering of data for example, and plot types may vary from dendrograms and heat maps to scatter plots. As a student working on this project, you will be guided by mentors experienced in working with the underlying data as well as many open source technologies we use. Since the most effective data visualisation comes from understanding the data structure, there is a data science element to this project.</p>
							<p class="card-text" style="text-align: left;">Interested? Read on for more details on how to get involved.</p>
							<div class="embed-responsive embed-responsive-16by9">
								<a href="https://www.stemformatics.org/atlas" target="_blank">
									<img src="https://jacks-centos7.sfo2.digitaloceanspaces.com/Random/Screen%20Shot%202020-01-02%20at%201.43.31%20pm.png" class="embed-responsive-item">
								</a>
							<!-- <iframe class="embed-responsive-item" src="https://www.stemformatics.org/atlas" allowfullscreen></iframe> -->
							</div>
							<h6 class="card-title" style="text-align: left;">Input:</h6>
							<p class="card-text" style="text-align: left;">In this project, there are primarily two types of input data, and we can call these "expression" data and "sample" data.</p>
							<p class="card-text" style="text-align: left;">Expression data represent gene expression measurements performed by machines on biological samples. For example, "TP53" gene has value of 50 in "sample1" and 0 in "sample2". Usually an expression dataset is thought of as a pandas DataFrame object (download an example text file <a href="https://data.stemformatics.org/files/notta_expression.tsv">here</a>, which has gene ids as row ids, and sample ids as column names.</p>
							<p class="card-text" style="text-align: left;">Sample data represent metadata about the biological samples which were measured. For example, "sample1" came from blood of male patient, while "sample2" came from bone marrow of a female patient. An example sample data file can be downloaded <a href="https://data.stemformatics.org/files/notta_samples.tsv">here</a>. This can also be a pandas DataFrame object, with sample ids (matching the columns of expression) as row ids, and different sample groups as column names.</p>
							<p class="card-text" style="text-align: left;">Note that expression data are very large and we don't usually plot all the values - we may select some genes to plot on a page. And sample data may contain columns which are not always informative (say all samples were from same tissue).</p>
							<h6 class="card-title" style="text-align: left;">Output:</h6>
							<p class="card-text" style="text-align: left;">Ideally we want to create interactive javascript pages which show plots from such input data that users can understand and query. For example, we may want to show if two genes are correlated with each other in value, so we may perform gene vs gene plot, and colour by a sample group. As a successful student of this project, you may see your plotting code deployed on a production server eventually and used by thousands of researchers around the world! To get started for this project, have a go at creating some gene vs gene scatterplots using plotly - you can even do this on a python notebook rather than a javascript page. You can use the example dataset files mentioned above. Perhaps find some examples where gene vs gene correlation is high vs low, and if these may separate samples from one group to another. Feel free to use our <a href="https://gitter.im/stemformatics/Lobby" target="_blank">gitter page</a> for questions.</p>
						</div>
					</div>
				</a>
			</b-col>
			</b-row>

			<br>
			<br>

			<b-row>
			<b-col>
				<a id="metadata_curation">
					<div class="card" >
						<div class="card-body">
							<h5 class="card-title" style="text-align: left;">Metadata Curation</h5>
							<!-- <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6> -->
							<p class="card-text" style="text-align: left;">Stemformatics has an extensive and well curated set of data descriptions (metadata), which store information about biological samples whose measurements were made by machines. An example may be a blood sample which was derived under some experimental condition, representing a cell type which may be important for fighting infection. As Stemformatics hosts hundreds of datasets comprising of tens of thousands of samples, it is not always easy to store very rigorous and well harmonised metadata. This project aims to improve this aspect of Stemformatics through user interfaces and data validation mechanisms. More accurate and rigorous metadata leads to less false positives and more opportunities to make exciting scientific discoveries.</p>
							<p class="card-text" style="text-align: left;">Interested? Read on for more details on how to get involved.</p>
							<div class="embed-responsive embed-responsive-16by9">
								<img src="https://jacks-centos7.sfo2.digitaloceanspaces.com/Random/Screen%20Shot%202020-01-02%20at%203.23.09%20pm.png" class="embed-responsive-item">
							<!-- <iframe class="embed-responsive-item" src="https://www.stemformatics.org/datasets/search" allowfullscreen></iframe> -->
							</div>
							<h6 class="card-title" style="text-align: left;">Input:</h6>
							<p class="card-text" style="text-align: left;">In this project, we will work within our new "data portal" application (currently only in prototype form), which aims to separate the data in Stemformatics from the web application component. The data portal application (built using nodejs) already has pages which can read and write metadata fields, and we want to improve these pages with more functionality. These pages will form the basis for this project. The data comes from postgresql tables, but you can see an example from just one dataset in text format <a href="https://data.stemformatics.org/files/notta_samples.tsv">here</a>.</p>
							<h6 class="card-title" style="text-align: left;">Output:</h6>
							<p class="card-text" style="text-align: left;">The output for this project involves 2 components:</p>
							<ul>
								<li><p class="card-text" style="text-align: left;">Improve the current pages for updating the metadata in the data portal. For example, allow a user to update multiple fields easily by grouping fields together.</p></li>
								<br>
								<li><p class="card-text" style="text-align: left;">Write data validation/checking scripts that can work with user interfaces to ensure that good rigorous data entries are made. We want to avoid "Homo sapiens" and "homo sapiens" to be separate entities in the database for example.</p></li>
							</ul>
							<p class="card-text" style="text-align: left;">To get started, play around with the vuejs implementation of <a href="https://www.ag-grid.com/vuejs-grid/" target="_blank">ag-grid</a>, which is what we're currently using for data updates. Imagine you have a table with hundreds of rows and tens of columns that you want to update using this javascript library. How would you update multiple values together? How would you validate the updates? Feel free to use our gitter <a href="https://gitter.im/stemformatics/Lobby" target="_blank">page</a> for questions.</p>
						</div>
					</div>
				</a>
			</b-col>
			</b-row>

			<br>
			<br>

			<b-row>
			<b-col>
				<a id="api_authorization">
					<div class="card" >
						<div class="card-body">
							<h5 class="card-title" style="text-align: left;">API Authorization</h5>
							<!-- <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6> -->
							<p class="card-text" style="text-align: left;">Future iterations of the data portal will include functionality for third party access to our dataset resources via the API. We are a global collaboration and our users access the platform from locations internationally. We need a way of securing our API resources, and a control mechanism for providing access to authorized parties. JSON Web Tokens allow a means of client server communication which is independent of session context (i.e. is a stateless communication protocol) meaning each transmission is processed in isolation regardless of previous session context. The goal for this project will be to prototype a scaffolded replica of our production API and implement a modern token authorisation framework for integration with a hierarchical user access schema.</p>
							<div class="embed-responsive embed-responsive-16by9">
								<a href="https://api-dp.stemformatics.org/" target="_blank"><img src="https://jacks-centos7.sfo2.digitaloceanspaces.com/Random/Screen%20Shot%202020-01-03%20at%2010.37.46%20am.png" class="embed-responsive-item"></a>
							</div>
							<h6 class="card-title" style="text-align: left;">Input:</h6>
							<p class="card-text" style="text-align: left;">To get started with this project, you can either bring your own working sample API code (preferably flask) or download a boilerplate sample from <a href="https://github.com/realpython/flask-jwt-auth" target="_blank">here</a>.  Our <a href="https://bitbucket.org/stemformatics/dataportal_flask_api/src/master/flask_api_dp/app.py" target="_blank">current API</a> already comes with JWT integration pre-loaded, however we need to contrive a suitable schema/database to handle the authorization functionality. Our user table resides in Postgresql, and it contains a base-level user access model for internal members only, but this will need to be expanded upon to accommodate external use cases.</p>
							<h6 class="card-title" style="text-align: left;">Output:</h6>
							<p class="card-text" style="text-align: left;">The desired output for this project will be for a well-documented, maintainable web token authorisation system to be integrated into our production API. Try to scaffold your own version of what you think the system should look like. Keep in mind that there will be requests for access from multiple different organisations, each of whom will have different user authentication requirements based on their role. For example, a scientist may only require read-only auth to a resource, whereas a data annotator or analyst will need to have CRUD capabilities. *Extra points: It would be great if we could also develop a back-end admin user interface to streamline the process of user creation, auth and deletion – however this is something that can be added later and is not essential.</p>
						</div>
					</div>
				</a>
			</b-col>
			</b-row>

			<br>
			<br>

		</b-row>

		</b-col>

		<go-top bg-color="#a64dff"></go-top>

		</b-row>
	</b-container>

</div>
</template>

<script>
import GoTop from '@inotom/vue-go-top';

export default {
	components: {
		GoTop
	}
}
</script>

<style scoped>
.card {
  width: 100%;
}
p {
  color: black;
}
.right {
  height: 100vh;
  overflow: hidden;
  overflow-y: scroll; 
  text-align: center;
}
</style>
