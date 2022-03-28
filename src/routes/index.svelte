<script>
let title = 'Ninja Gaming Guid'

const updateTitle = () => {
	// もしもタイトルが 'Ninja Gaming Guid' であれば、タイトルを 'complete different' に変更する
	// 反対に、もしもタイトルが 'complete different' であれば、タイトルを 'Ninja Gaming Guid' に変更する
	if (title === 'Ninja Gaming Guid') {
		title = 'complete different'
	} else {
		title = 'Ninja Gaming Guid'
	}
}
</script>

<div class="index">
	<h2 class="title">{title}</h2>
	<p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ratione distinctio sit harum labore molestias facere officiis voluptatibus sapiente autem placeat nihil repellat ad sed eligendi possimus, aliquam doloribus porro repellendus.</p>
	<button class="button" on:click={updateTitle}>update title</button>
</div>

<style>
.index {
	text-align: center;
	display: block;
	margin: 20px auto;
}

.title {
	color: #ff0000;
	font-size: 2em;
	font-weight: bold;
}
</style>
