<template>
	<section class="section">
		<div class="container">
			<h1 class="title">Hi, world!</h1>
			<h2 class="subtitle">As you can see, there are plenty of links. Also you
				can submit and share one useful link for all in FCC Caracas</h2>
			<div class="field">
				<div class="control is-medium has-icons-left">
					<input type="text" class="input is-medium is-rounded" placeholder="Search">
				</div>
			</div>
			<div class="columns">
				<div class="column is-half">
					<pick-form></pick-form>
				</div>
				<div class="column">
					<one-pick></one-pick>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
import OnePick from './components/OnePick.vue'
import PickForm from './components/PickForm.vue'

export default {
  name: 'app',
	components: {
		OnePick, PickForm
	}
}
</script>

<style lang="sass">
/* Required files */
@import '~bulma/sass/utilities/_all'
@import '~bulma/sass/base/_all'

/* Components */
@import '~bulma/sass/components/media'

/* Elements */
@import '~bulma/sass/elements/box'
@import '~bulma/sass/elements/button'
@import '~bulma/sass/elements/container'
@import '~bulma/sass/elements/form'
@import '~bulma/sass/elements/image'
@import '~bulma/sass/elements/tag'
@import '~bulma/sass/elements/title'

/* Layout */
@import '~bulma/sass/layout/section'

/* Grid */
@import '~bulma/sass/grid/columns'

</style>
