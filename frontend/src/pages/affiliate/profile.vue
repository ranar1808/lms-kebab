<template>
<div>
						<div class="col-lg-12">
							<nav class="breadcrumb_widgets" aria-label="breadcrumb mb30">
								<h4 class="title float-left">User Profile</h4>
								<ol class="breadcrumb float-right">
							    	<li class="breadcrumb-item"><a href="#">Home</a></li>
							    	<li class="breadcrumb-item active" aria-current="page">Dashboard</li>
								</ol>
							</nav>
						</div>
						<div class="col-lg-12">
							<div class="my_course_content_container">
								<div class="my_setting_content mb30">
									<div class="my_setting_content_header">
										<a href="../affiliate/edit_profile" class="btn btn-primary pull-right">Edit profile</a>
										<div class="my_sch_title">
											<h4 class="m0">Personal Details</h4>
										</div>
									</div>
									<div class="row my_setting_content_details pb0">
										<div class="col-xl-2">
											<img src="https://i.imgur.com/6XESUuX.jpg" class="img-profile">
										</div>
										<div class="col-xl-10">
											<div class="row">
												<div class="col-xl-4">
													<div class="my_profile_setting_input form-group">
												    	<label for="formGroupExampleInput1">First Name</label>
												    	<p>Hasan</p>
													</div>
													<div class="my_profile_setting_input form-group">
												    	<label for="formGroupExampleInput2">Occupation</label>
												    	<p>Student</p>
													</div>
												</div>
												<div class="col-xl-4">
													<div class="my_profile_setting_input form-group">
												    	<label for="formGroupExampleInput2">Last Name</label>
												    	<p>Saskeh</p>
													</div>
													<div class="my_profile_setting_input form-group">
												    	<label for="exampleInputPhone">Birthday</label>
												    	<p>21 January 1990</p>
													</div>
												</div>
												<div class="col-xl-4">
													<div class="my_profile_setting_input form-group">
												    	<label for="formGroupExampleInput2">Email</label>
												    	<p>hasansas@gmail.com</p>
													</div>
												</div>
											</div>
										</div>
									</div>
									<div class="my_setting_content_header style2">
										<div class="my_sch_title">
											<h4 class="m0">Location</h4>
										</div>
									</div>
									<div class="row my_setting_content_details pb0">
										<div class="col-xl-12">
											<div class="row">
												<div class="col-xl-4">
													<div class="my_profile_setting_input form-group">
												    	<label for="formGroupExampleInput1">Country</label>
												    	<p>Indonesia</p>
													</div>
													<div class="my_profile_setting_input form-group">
												    	<label for="formGroupExampleInput2">City</label>
												    	<p>Yogyakarta</p>
													</div>
												</div>
												<div class="col-xl-8">
													<div class="my_profile_setting_input form-group">
												    	<label for="formGroupExampleInput2">Address</label>
												    	<p>Jl. Kusumanegera No.250, Gedongkuning, Kotagede, Yogyakarta, DIY</p>
													</div>
												</div>
											</div>
										</div>
									</div>
									<div class="my_setting_content_header style3">
										<div class="my_sch_title">
											<h4 class="m0">Bank account</h4>
										</div>
									</div>
									<div class="row my_setting_content_details">
									    <div class="col-xl-6">
									    	<div class="my_profile_setting_input form-group">
												<label for="formGroupExampleInput1">Bank name</label>
												<p>Bank Mandiri</p>
											</div>
									    </div>
									    <div class="col-xl-6">
											<div class="my_profile_setting_input form-group">
												<label for="formGroupExampleInput1">No. rekening</label>
												<p>456700656</p>
											</div>
									    </div>
									</div>
								</div>
							</div>
						</div>
					</div>  

</template>

<script>
import { mapMutations, mapGetters } from "vuex";
import { ConfirmDelete } from "~/components/admin";
import courses from "~/services/courses";

export default {
  head: {
    title: "Affiliate"
  },
  layout: "affiliate"
};

</script>
