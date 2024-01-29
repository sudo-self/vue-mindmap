<template>
	<div id="app">
		<mindmap
			:nodes="nodes"
			:connections="connections"
			:editable="true"
		/>
	</div>
</template>

<script>
import map from "./map";

export default {
  name: "app",
  data() {
    return { ...map };
  }
};
</script>
