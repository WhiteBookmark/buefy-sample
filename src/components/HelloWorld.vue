<template>
	<section style="margin-top:25px;">
		<b-message
			title="Danger with icon"
			type="is-danger"
			has-icon
			aria-close-label="Close message"
		>
			Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce id
			fermentum quam. Proin sagittis, nibh id hendrerit imperdiet, elit
			sapien laoreet elit
			<div class="buttons">
				<b-button type="is-danger" icon-left="delete">
					Delete
				</b-button>

				<b-button type="is-danger" icon-right="delete">
					Delete
				</b-button>

				<b-button type="is-danger" icon-right="delete" />
			</div>
		</b-message>

		<b-message
			title="Success with icon"
			type="is-success"
			has-icon
			aria-close-label="Close message"
		>
			Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce id
			fermentum quam. Proin sagittis, nibh id hendrerit imperdiet, elit
			sapien laoreet elit
		</b-message>

		<b-message
			title="Info with icon"
			type="is-info"
			has-icon
			aria-close-label="Close message"
		>
			Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce id
			fermentum quam. Proin sagittis, nibh id hendrerit imperdiet, elit
			sapien laoreet elit
		</b-message>

		<b-message
			title="Warning with icon"
			type="is-warning"
			has-icon
			aria-close-label="Close message"
		>
			Lorem ipsum dolor sit amet, consectetur warning elit. Fusce id
			fermentum quam. Proin sagittis, nibh id hendrerit imperdiet, elit
			sapien laoreet elit
		</b-message>

		<b-message
			title="Dark with custom icon"
			type="is-dark"
			has-icon
			icon="account"
			aria-close-label="Close message"
		>
			Lorem ipsum dolor sit amet, consectetur warning elit. Fusce id
			fermentum quam. Proin sagittis, nibh id hendrerit imperdiet, elit
			sapien laoreet elit
		</b-message>
	</section>
</template>

<script>
export default {
	name: 'HelloWorld',
	props: {
		msg: String,
	},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
	margin: 40px 0 0;
}
ul {
	list-style-type: none;
	padding: 0;
}
li {
	display: inline-block;
	margin: 0 10px;
}
a {
	color: #42b983;
}
</style>
